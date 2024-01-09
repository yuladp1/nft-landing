<template>
<div class="mx-[8%]">
   <header class="my-7">
    <nav class="flex justify-between text-white ">
        <ul class="flex items-center gap-10 text-white">
            <li class=" ">Marketplace</li>
            <li class="">Artists</li>
            <li class="">Community</li>
            <li class="">Collections</li>
        </ul>
        <button class="py-3 px-10 rounded-lg bg-lime-500 transition ease-in-out delay-150 duration-500 hover:bg-white hover:text-lime-500">Contact</button>
    </nav>
    
   </header>
   <slot></slot>


   <footer class="mt-[300px] text-white flex justify-between">
    <div class="flex flex-col gap-[24px] w-[21%]"> 
        <p class="text-white">Discover NFTs by category, track the latest drop, and and follow the collections you love. Enjoy it!</p>
        <div class="flex gap-[5px] ">
            <img src="../assets/icons/FB.svg" alt="">
            <img src="../assets/icons/telegram.svg" alt="">
            <img src="../assets/icons/twitter.svg" alt="">
            <img src="../assets/icons/linkedin.svg" alt="">
        </div>
    </div>

    <nav class="flex w-[50%] justify-between">
        <ul>
            <li> Explore</li>
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

<style scoped>
ul {
    font-size: 16px;
}

</style>