<template>
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
