<template>
  <section
    class="flex flex-col gap-y-[20px] mt-[100px] md:flex-row md:justify-between gap-[10%] md:mt-[150px]"
  >
    <div class="w-full md:w-[45%] grow-1 shrink-1 flex flex-col">
      <h1 class="">
        Discover and Collect The Best NFTs
        <span class="text-lime-500"> Digital Art. </span>
      </h1>
      <p class="hero-text text-base pt-[20px] leading-[160%] shrink-1">
        Get started with the easiest and most secure platform to buy and trade digital ART
        and NFT’s. Start exploring the world of digital art and NFTs today and take
        control of your digital assets with confidence!
      </p>
      <div class="flex gap-[20px] pt-[40px] shrink-1">
        <div><button class="">Explore Now</button></div>
        <div><button class="">Learn more</button></div>
      </div>
      <div class="pt-72px flex justify-between pt-[72px] text-[3rem] shrink-1">
        <div
          class="pr-[28px] border-r-[1px] border-lime flex flex-col justify-between shrink-1"
        >
          <p><span class="text-lime-500 shrink-1">8.9</span>K</p>
          <p class="text-base shrink-1">Art work</p>
        </div>
        <div class="pr-[28px] border-r-[1px] border-lime shrink-1">
          <p>
            <span class="text-lime-500 shrink-1">{{ targetValue }}</span
            >K
          </p>
          <p class="pt-[8px] text-base shrink-1">Artist</p>
        </div>
        <div class="pr-[28px] shrink-1">
          <p><span class="text-lime-500 shrink-1">87</span>K</p>
          <p class="pt-[8px] text-base shrink-1">Collection</p>
        </div>
      </div>
    </div>

    <div
      class="image-hero md:mr-[40px] mx-auto relative w-[300px] h-[400px] md:w-[464px] md:h-[544px] rounded-3xl flex grow-0 shrink-1 bg-no-repeat bg-cover"
    >
      <div>
        <figure
          class="container-stars absolute w-[140px] h-[140px] top-[50%] left-[-70px] z-10 animate-pulse"
        >
          <img
            src="../assets/images/Star-center.svg"
            alt=""
            class="absolute top-[38%] left-[38%]"
          />
        </figure>
      </div>
      <!-- Section above the hero-image -->
      <div
        class="absolute w-[304px] p-[20px] bg-[#131E3A] flex flex-col align-center z-10 bottom-[-50px] right-[-30px] md:right-[-50px] rounded-[16px] border-2 border-transparent border-y-lime-900"
      >
        <div class="flex justify-between w-[100%] rounded-[16px]">
          <div>
            <p class="text-lime-500">Ends in</p>
            <p>05:45:47</p>
          </div>
          <div>
            <p class="text-lime-500">Current bit</p>
            <p>0.24ETH</p>
          </div>
        </div>
        <p
          class="w-[100%] mt-[24px] leading-[52px] border-[1px] border-lime-500 hover:border-white hover:text-lime-500 rounded-lg flex justify-around"
        >
          <span>Place a bit</span>
        </p>
      </div>
    </div>
  </section>
</template>

<script setup>
definePageMeta({
  layout: "default",
});
const targetValue = ref(0);
const duration = 2000;
const interval = 20;
const steps = duration / interval;
const stepValue = targetValue.value / steps;
let currentValue = 0;
const counterInterval = ref(null);

const updateCounter = () => {
  currentValue += stepValue;
  targetValue.value = Math.round(currentValue);
  if (currentValue >= 65) {
    clearInterval(counterInterval.value);
  }
};

onMounted(() => {
  counterInterval.value = setInterval(updateCounter, interval);
  updateCounter();
});
</script>

<style scoped>
.container-stars {
  background-image: url("/assets/images/group.svg");
  background-size: contain;
}

.image-hero {
  background-image: url("/assets/images/hero.png");
}
</style>
