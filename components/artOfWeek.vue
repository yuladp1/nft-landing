<template>
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
</template>
<style scoped>
.container-clocks::before {
  content: url("../assets/icons/clock.svg");
  padding-right: 12px;
}

.container-etherium::before {
  content: url("../assets/icons/ethereum-classic.svg");
  padding-right: 4px;
}
</style>
