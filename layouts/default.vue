<template>
  <div class="mx-[8%]">
    <header class="w-full">
      <!-- Navigation for full-screen -->
      <div
        class="w-full h-[80px] fixed top-[20px] hidden md:flex items-center justify-between bg-white/20 z-10 px-2 rounded-2xl"
      >
        <nav class="flex justify-between">
          <ul class="flex items-center gap-10">
            <li class=" ">Marketplace</li>
            <li class="">Artists</li>
            <li class="">Community</li>
            <li class="">Collections</li>
          </ul>
        </nav>

        <button class="w-auto ml-auto">Contact</button>
      </div>
      <!--  -------------------------------------    -->

      <!-- Navigation for small devices -->
      <div
        class="flex content-center items-center w-full h-[60px] z-30 bg-white/50 fixed top-[20px] md:hidden"
      >
        <div class="flex flex-col w-full justify-between items-center">
          <div class="flex w-full justify-between content-center justify-center">
            <button class="w-auto ml-2">Contact</button>
            <div
              id="burger"
              @click="() => (burgerShow = !burgerShow)"
              :class="{ active: burgerShow }"
            ></div>
          </div>
        </div>
        <nav
          :class="{ hidden: !burgerShow, block: burgerShow }"
          class="flex flex-col w-full items-center gap-10 bg-white/20 mt-[12px] z-30 text-[30px]"
        >
          <ul class="flex flex-col w-full items-center gap-10 bg-black/90 py-5">
            <li class="text-[30px]">Marketplace</li>
            <li class="text-[30px]">Artists</li>
            <li class="text-[30px]">Community</li>
            <li class="text-[30px]">Collections</li>
          </ul>
        </nav>
      </div>
      <!-- --------------------------------- -->
    </header>

    <slot></slot>

    <footer class="mt-[300px] flex justify-between">
      <div class="flex flex-col gap-[24px] w-[21%]">
        <p class="">
          Discover NFTs by category, track the latest drop, and and follow the collections
          you love. Enjoy it!
        </p>
        <div class="flex gap-[5px]">
          <img src="../assets/icons/FB.svg" alt="" />
          <img src="../assets/icons/telegram.svg" alt="" />
          <img src="../assets/icons/twitter.svg" alt="" />
          <img src="../assets/icons/linkedin.svg" alt="" />
        </div>
      </div>

      <nav class="flex w-[50%] justify-between">
        <ul>
          <li>Explore</li>
          <li>Art Sign In</li>
          <li>Collectibles</li>
          <li>Domain Name</li>
          <li>Utility</li>
        </ul>
        <ul>
          <li>Statistic</li>
          <li>Ranking</li>
          <li>Collectibles</li>
          <li>Activity</li>
        </ul>
        <ul>
          <li>Company</li>
          <li>About Us</li>
          <li>Career</li>
          <li>Support</li>
          <li>Partners</li>
        </ul>
        <ul>
          <li>Resources</li>
          <li>Help Center</li>
          <li>Platform Status</li>
          <li>Blog</li>
        </ul>
      </nav>
    </footer>
  </div>
</template>

<script setup>
import { onMounted } from "vue";
var burgerShow = ref(false);
onMounted(() => {});
</script>

<style scoped>
#burger {
  position: relative;
  border: none;
  background: transparent;
  width: 40px;
  height: 26px;
}

#burger::before,
#burger::after {
  content: "";
  left: 0;
  position: absolute;
  display: block;
  width: 100%;
  height: 4px;
  border-radius: 10px;
  background: #000;
}

#burger::before {
  top: 0;
  box-shadow: 0 11px 0 #000;
}

#burger::after {
  bottom: 0;
}

#burger::before {
  transition: box-shadow 0.3s 0.15s, top 0.3s 0.15s, transform 0.3s;
}

#burger::after {
  transition: bottom 0.3s 0.15s, transform 0.3s;
}

#burger.active::before {
  top: 11px;
  transform: rotate(45deg);
  box-shadow: 0 6px 0 rgba(0, 0, 0, 0);
  transition: box-shadow 0.15s, top 0.3s, transform 0.3s 0.15s;
}

#burger.active::after {
  bottom: 11px;
  transform: rotate(-45deg);
  transition: bottom 0.3s, transform 0.3s 0.15s;
}
</style>
