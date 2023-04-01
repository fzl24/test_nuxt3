<template>
    
    <div id="animation-carousel" class="relative w-full p-3" data-carousel="static">
        <!-- Carousel wrapper -->
        <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
            <!-- Item 1 -->
            <div class="hidden duration-200 ease-linear" data-carousel-item>
                <img src="~/assets/img/crl-1.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
            </div>
            <!-- Item 2 -->
            <div class="hidden duration-200 ease-linear" data-carousel-item>
                <img src="~/assets/img/crl-2.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
            </div>
        </div>
        <!-- Slider controls -->
        <button type="button" class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
            <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path></svg>
                <span class="sr-only">Previous</span>
            </span>
        </button>
        <button type="button" class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
            <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                <span class="sr-only">Next</span>
            </span>
        </button>
    </div>



    <div class="grid grid-cols-4 gap-2 flex justify-items-center py-7">
        <div class="max-w-xs bg-white border border-gray-200 rounded-lg shadow-lg border-1">
            <a href="#">
                <img class="rounded-t-lg" src="~/assets/img/Genshin.png" alt="" />
            </a>
            <div class="p-4">
                <nuxt-link to="/games/Genshin Impact">
                    <span class="mb-2 text-sm font-bold tracking-tight text-gray-700 text-lg">Genshin Impact</span>
                </nuxt-link>
            </div>
            <div class="p-4">
                <nuxt-link to="/games/Genshin Impact">
                    <button class="p-4 bg-blue-600 rounded-md w-full font-bold text-white text-xl">
                        TOP UP
                    </button>
                </nuxt-link>
            </div>
        </div>
        <div class="max-w-xs bg-white border border-gray-200 rounded-lg shadow-lg border-1">
            <a href="#">
                <img class="rounded-t-lg" src="~/assets/img/mel.webp" alt="" />
            </a>
            <div class="p-4">
                <nuxt-link to="/games/mobile_legend">
                    <span class="mb-2 text-sm font-bold tracking-tight text-gray-700 text-lg">Mobile Legend</span>
                </nuxt-link>
            </div>
            <div class="p-4">
                <nuxt-link to="/games/mobile_legend">
                    <button class="p-4 bg-blue-600 rounded-md w-full font-bold text-white text-xl">
                        TOP UP
                    </button>
                </nuxt-link>
            </div>
        </div>
        <div class="max-w-xs bg-white border border-gray-200 rounded-lg shadow-lg border-1">
            <a href="#">
                <img class="rounded-t-lg" src="~/assets/img/pubg.png" alt="" />
            </a>
            <div class="p-4">
                <nuxt-link to="/games/pubg">
                    <span class="mb-2 text-sm font-bold tracking-tight text-gray-700 text-lg">PUBG</span>
                </nuxt-link>
            </div>
            <div class="p-4">
                <nuxt-link to="/games/pubg">
                    <button class="p-4 bg-blue-600 rounded-md w-full font-bold text-white text-xl">
                        TOP UP
                    </button>
                </nuxt-link>
            </div>
        </div>
        <div class="max-w-xs bg-white border border-gray-200 rounded-lg shadow-lg border-1">
            <a href="#">
                <img class="rounded-t-lg" src="~/assets/img/valorant.png" alt="" />
            </a>
            <div class="p-4">
                <nuxt-link to="/games/valorant">
                    <span class="mb-2 text-sm font-bold tracking-tight text-gray-700 text-lg">Valorant</span>
                </nuxt-link>
            </div>
            <div class="p-4">
                <nuxt-link to="/games/valorant">
                    <button class="p-4 bg-blue-600 rounded-md w-full font-bold text-white text-xl">
                        TOP UP
                    </button>
                </nuxt-link>
            </div>
        </div>
    </div>

    
    
</template>

<script setup>
    definePageMeta({
        layout: 'default'
    })
</script>

<style scoped>
    h2 {
        color: rgb(214, 255, 80);
    }
</style>