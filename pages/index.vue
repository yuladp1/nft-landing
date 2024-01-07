<template>
    <section class="flex text-white justify-between shrink-1 gap-[70px]">
        <div class="w-[45%] grow-1 shrink-1 flex flex-col">
            <h1 class="text-[64px] font-medium leading-[120%] shrink-1">Discover and Collect The Best NFTs <span
                    class="text-lime-500"> Digital Art. </span>
            </h1>
            <p class="hero-text text-[16px] pt-[20px] leading-[160%] shrink-1">Get started with the easiest and most secure
                platform to buy and trade digital ART and NFT’s. Start exploring the world of digital art and NFTs today and
                take control of your digital assets with confidence!</p>
            <div class="flex gap-[20px] pt-[40px] shrink-1">
                <button class="">Explore Now</button>
                <button class="">Learn more</button>
            </div>
            <div class="pt-72px flex justify-between  pt-[72px] text-[48px] shrink-1">
                <div class="pr-[28px] border-r-[1px] border-lime flex flex-col justify-between shrink-1">
                    <p><span class="text-lime-500 shrink-1">8.9</span>K</p>
                    <p class="text-[16px] shrink-1">Art work</p>
                </div>
                <div class="pr-[28px] border-r-[1px] border-lime shrink-1">
                    <p><span class="text-lime-500 shrink-1">65</span>K</p>
                    <p class="pt-[8px] text-[16px] shrink-1">Artist</p>
                </div>
                <div class="pr-[28px] shrink-1">
                    <p><span class="text-lime-500 shrink-1">87</span>K</p>
                    <p class="pt-[8px] text-[16px] shrink-1">Collection</p>
                </div>
            </div>
        </div>

        <div class="image-hero relative w-[464px] h-[544px] rounded-3xl flex grow-0 shrink-1  bg-no-repeat bg-cover">
            <figure class="container-stars absolute w-[140px] h-[140px] top-[50%] left-[-70px] z-10 animate-pulse">
                <img src="../assets/images/Star-center.svg" alt="" class="absolute top-[38%] left-[38%]">
            </figure>

            <div
                class="absolute w-[304px] p-[20px] bg-[#131E3A] flex flex-col align-center z-10 bottom-[-50px] right-[-50px]">
                <div class="flex justify-between w-[100%]">
                    <div>
                        <p class="text-lime-500">Ends in</p>
                        <p>05:45:47</p>
                    </div>
                    <div>
                        <p class="text-lime-500">Current bit</p>
                        <p>0.24ETH</p>
                    </div>
                </div>
                <p class="w-[100%] mt-[24px] leading-[52px] border-[1px] border-lime-500 hover:border-white hover:text-lime-500 rounded-lg flex justify-around"> <span>Place a bit</span></p>
            </div>
        </div>
    </section>
    
    
<!-- section "Amazing and Super Unique Art of This Week" -->  
<section class="flex justify-between mt-[92px]">
    <h2 class="text-5xl w-[530px] text-white shrink-1 leading-[120%]"><span class="text-lime-500">Amazing</span> and Super Unique Art of This <span class="text-lime-500">Week</span></h2>
<button class="self-end">See all</button>
</section>


<!--            -->
</template>

<script setup >
definePageMeta({
    layout: 'default'
})
</script>

<style scoped>
.hero-text {
    font-family: 'Spectral', serif;
}

.container-stars {
    background-image: url('../assets/images/group.svg');
    background-size: contain;
}

.image-hero {
    background-image: url('../assets/images/hero.png');
}</style>