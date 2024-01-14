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

  <!-- section "Amazing and Super Unique Art of This Week" -->
  <section
    class="flex flex-col justify-start md:flex-row md:justify-between mt-[60px] md:mt-[92px]"
  >
    <h2>
      <span class="text-lime-500">Amazing</span> and Super Unique Art of This
      <span class="text-lime-500">Week</span>
    </h2>
    <button class="mx-0 w-full md:w-auto md:self-end">See all</button>
  </section>

  <section
    class="w-[100%] flex flex-col gap-y-[30px] md:flex-row pt-[64px] justify-between"
  >
    <div
      class="md:w-[32%] flex-col bg-[#131E3A] rounded-[28px] border-2 border-transparent border-y-lime-900 p-[20px]"
    >
      <div class="relative pb-[100%] w-[100%] rounded-[16px]">
        <img
          src="../assets/images/art1.png"
          alt=""
          class="absolute object-cover w-[100%] h-[100%]"
        />
      </div>
      <div
        class="wrapper-text relative mt-[24px] flex flex-wrap items-center justify-between"
      >
        <span class="text-[24px]">Cyberpunk Cocomo</span>
        <span class="container-etherium flex text-base">490ETN</span>
      </div>
      <div class="mt-[16px] flex justify-between items-center flex-wrap">
        <div class="">
          <p class="text-[#838382] text-sm">Ending in</p>
          <div class="container-clocks flex text-base">03:24:56</div>
        </div>
        <p
          class="leading-[52px] py-[12px] px-[40px] border-[1px] border-lime-500 hover:border-white hover:text-lime-500 rounded-lg flex justify-around"
        >
          <span class="">Place a bit</span>
        </p>
      </div>
    </div>
    <div
      class="md:w-[32%] flex-col bg-[#131E3A] rounded-[28px] border-2 border-transparent border-y-lime-900 p-[20px]"
    >
      <div class="relative pb-[100%] w-[100%] rounded-[16px]">
        <img
          src="../assets/images/art2.png"
          alt=""
          class="absolute object-cover w-[100%] h-[100%]"
        />
      </div>
      <div
        class="wrapper-text relative mt-[24px] flex flex-wrap items-center justify-between"
      >
        <span class="text-[24px]">Cyberpunk Cocomo</span>
        <span class="container-etherium flex text-base">490ETN</span>
      </div>
      <div class="mt-[16px] flex flex-wrap justify-between items-center">
        <div class="">
          <p class="text-[#838382] text-sm">Ending in</p>
          <div class="container-clocks flex text-base">03:24:56</div>
        </div>
        <p
          class="leading-[52px] py-[12px] px-[40px] border-[1px] border-lime-500 hover:border-white hover:text-lime-500 rounded-lg flex justify-around"
        >
          <span class="">Place a bit</span>
        </p>
      </div>
    </div>
    <div
      class="md:w-[32%] flex-col bg-[#131E3A] rounded-[28px] border-2 border-transparent border-y-lime-900 p-[20px]"
    >
      <div class="relative pb-[100%] w-[100%] rounded-[16px]">
        <img
          src="../assets/images/art3.png"
          alt=""
          class="absolute object-cover w-[100%] h-[100%]"
        />
      </div>
      <div
        class="wrapper-text relative mt-[24px] flex flex-wrap items-center justify-between"
      >
        <span class="text-[24px]">Cyberpunk Cocomo</span>
        <span class="container-etherium flex text-base">490ETN</span>
      </div>
      <div class="mt-[16px] flex flex-wrap justify-between items-center">
        <div class="">
          <p class="text-[#838382] text-sm">Ending in</p>
          <div class="container-clocks flex text-base">03:24:56</div>
        </div>
        <p
          class="leading-[52px] py-[12px] px-[40px] border-[1px] border-lime-500 hover:border-white hover:text-lime-500 rounded-lg flex justify-around"
        >
          <span class="">Place a bit</span>
        </p>
      </div>
    </div>
  </section>
  <!--            -->

  <!-- Create And Sell Your Best NFTs -->
  <section class="flex flex-col md:flex-row gap-y-[30px] justify-between mt-[92px]">
    <div class="w-full md:basis-1/3">
      <div>
        <h2 class="md:basis-2/3">
          Create And Sell<span class="text-lime-500"> Best NFTs</span>
        </h2>
        <p class="pt-[20px]">
          Start exploring the world of digital art and NFTs today and take control of your
          digital assets with confidence!
        </p>
      </div>
      <div class="flex justify-start gap-[10px] pt-[40px]">
        <div><button>Create Now</button></div>
        <div><button>Learn more</button></div>
      </div>
    </div>

    <div class="relative w-[50%] h-[300px] md:w-[32%] md:h-[475px] md:mx-0">
      <figure class="absolute top-0 right-0">
        <img src="../assets/images/bestNFT1.png" alt="" class="object-cover" />
      </figure>
      <figure class="absolute left-[-80%] top-[30%] w-[100%]">
        <img src="../assets/images/bestNFT2.png" alt="" class="object-cover" />
      </figure>
    </div>
  </section>

  <!-- Popular Artists On This Week -->

  <section class="pt-[60px] md:pt-[100px]">
    <div class="flex flex-col md:flex-row justify-between items-center">
      <h2 class="basis-2/5">
        Popular <span class="text-lime-500">Artists</span> On This Week
      </h2>
      <button class="mx-2 mb-4 w-full md:w-auto">See all</button>
    </div>

    <!-- Images block -->

    <div class="flex w-full gap-4">
      <div class="grid gap-4 grid-cols-10 grid-auto-flow w-[68%]">
        <img
          src="../assets//images/artist1.png"
          alt=""
          class="object-cover grid grid-cols-subgrid gap-4 col-span-4 rounded-2xl w-full h-full"
        />

        <img
          src="../assets//images/artist2.png"
          alt=""
          class="grid grid-cols-subgrid gap-4 col-span-6 object-cover rounded-2xl w-full h-full"
        />

        <img
          src="../assets//images/artist3.png"
          alt=""
          class="grid grid-cols-subgrid gap-4 col-span-5 object-cover w-full h-full"
        />
        <img
          src="../assets//images/artist4.png"
          alt=""
          class="grid grid-cols-subgrid gap-4 col-span-5 rounded-2xl object-cover w-full h-full"
        />
      </div>

      <div class="">
        <img
          src="../assets//images/artist5.png"
          alt=""
          class="object-cover rounded-2xl w-full h-full"
        />
      </div>
    </div>
  </section>

  <!-- 140 520   1290 Subscribe And get our Updates Every Week -->
  <section
    class="mt-[90px] flex flex-col md:flex-row gap-y-[30px] justify-between w-full"
  >
    <div class="w-[31%]">
      <figure class="relative">
        <img src="../assets/images/subscribe1.png" alt="" class="absolute object-cover" />
      </figure>
      <figure class="relative pt-[30%] pl-[60%]">
        <img src="../assets/images/subscribe2.png" alt="" class="absolute object-cover" />
      </figure>
    </div>

    <div class="md:w-[40%]">
      <h2 class="w-full">
        Subscribe And <span class="text-lime-500"> get our Updates</span> Every Week
      </h2>
      <p class="pt-[20px] pb-[40px]">
        We have a blog related to NFT so we can share thoughts and routines on our blog
        which is updated weekly
      </p>
      <!-- Text-area and button -->
      <div class="flex">
        <input type="email" placeholder="Enter your e-mail" class="w-full bg-[#131E3A]" />
        <button>Subscribe</button>
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
  background-image: url("../assets/images/group.svg");
  background-size: contain;
}

.image-hero {
  background-image: url("../assets/images/hero.png");
}

.container-clocks::before {
  content: url("../assets/icons/clock.svg");
  padding-right: 12px;
}

.container-etherium::before {
  content: url("../assets/icons/ethereum-classic.svg");
  padding-right: 4px;
}
</style>
