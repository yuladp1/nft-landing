<template>
<div class="mx-[8%]">
   <header class="my-7">
    <nav class="flex justify-between text-white">
        <ul class="flex items-center gap-10 text-white">
            <li class="hover:underline hover:decoration-lime-500 hover:decoration-2 ">Marketplace</li>
            <li class="hover:underline hover:decoration-lime-500 hover:decoration-2">Artists</li>
            <li class="hover:underline hover:decoration-lime-500 hover:decoration-2">Community</li>
            <li class="hover:underline hover:decoration-lime-500 hover:decoration-2">Collections</li>
        </ul>
        <button class="py-3 px-10 rounded-lg bg-lime-500 transition ease-in-out delay-150 duration-500 hover:bg-white hover:text-lime-500">Contact</button>
    </nav>
    
   </header>
   <slot></slot>
   <footer>footer</footer>
</div>
</template>

<style scoped>
ul {
    font-family: 'Inter', sans-serif;
    font-size: 16px;
}
</style>