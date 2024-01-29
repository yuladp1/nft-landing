<template>
  <div class="observe">
    <HeroSection />
  </div>
  <!-- section "Amazing and Super Unique Art of This Week" -->
  <div class="observe">
    <ArtOfWeek />
  </div>
  <!-- Create And Sell Your Best NFTs -->
  <div class="observe">
    <CreateAndSell />
  </div>
  <!-- Popular Artists On This Week -->
  <div class="observe">
    <PopularArtists />
  </div>
  <!-- Subscribe And get our Updates Every Week -->
  <div class="observe">
    <SubscribeAndGet />
  </div>
</template>
<style>
/* class for starting point */
.observe {
  opacity: 0;
  transition: all 1s;
  margin-right: -100px;
}

/* class for visible section */
.inScreen {
  opacity: 1;
  margin-right: 0;
}
</style>
<script setup>
import { onMounted } from "vue";
onMounted(() => {
  if (typeof window !== "undefined") {
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((entry) => {
          const intersecting = entry.isIntersecting;
          entry.target.classList.toggle("inScreen", intersecting);
        });
        console.log(entries);
      },
      { threshold: 0.3 }
    );

    const elementsToObserve = document.getElementsByClassName("observe");
    Array.from(elementsToObserve).forEach((element) => {
      observer.observe(element);
    });
  }
});
</script>
