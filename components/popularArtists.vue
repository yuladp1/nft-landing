<template>
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
</template>
