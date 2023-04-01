<template>
    <div class="container">
        <div class="grid grid-cols-3 gap-4">
            <div>
                <a href="#" class="block p-6 bg-white border border-gray-200 rounded-lg shadow-lg hover:bg-gray-100">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">{{ id }}</h5>
                    <!-- <p class="font-normal text-gray-700">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p> -->
                    <img class="rounded-t-lg" src="~/assets/img/Genshin.png" alt="" />
                </a>
            </div>
            <div class="col-span-2 w-full">
                <a href="#" class="block p-6 bg-white border border-gray-200 rounded-lg shadow-lg hover:bg-gray-100">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900">1. Informasi UID Anda</h5>
                    <p class="font-normal text-gray-700">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
                </a>
            </div>
        </div>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    definePageMeta({
        layout: 'default'
    })
</script>

<style scoped>
    h4 {
        color: rgb(109, 109, 109);
    }
</style>