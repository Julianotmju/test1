<template>
  <MainLayout>

    <div class="flex items-center justify-center py-4 md:py-8 flex-wrap">
    <button type="button" @click="navigateTo('/fachadas')" class="text-gray-900 border border-white hover:border-gray-200 dark:border-gray-900 dark:bg-gray-900 dark:hover:border-gray-700 bg-white focus:ring-4 focus:outline-none focus:ring-gray-300 rounded-full text-base font-medium px-5 py-2.5 text-center me-3 mb-3 dark:text-white dark:focus:ring-gray-800">Fachadas</button>
    <button type="button" @click="navigateTo('/plotagem-auto')" class="text-gray-900 border border-white hover:border-gray-200 dark:border-gray-900 dark:bg-gray-900 dark:hover:border-gray-700 bg-white focus:ring-4 focus:outline-none focus:ring-gray-300 rounded-full text-base font-medium px-5 py-2.5 text-center me-3 mb-3 dark:text-white dark:focus:ring-gray-800">Plotagens</button>
</div>


<div class="flex items-center justify-center py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-5xl lg:text-6xl dark:text-white text-transparent bg-clip-text bg-gradient-to-r from-purple-500 to-cyan-500">
                LUMINOSO</h1>
        </div>


<div class="grid grid-cols-2 md:grid-cols-3 gap-4">
    <div>
        <img class="h-auto max-w-full rounded-lg" src="/imgs/luminosos/1.jpg" alt="">
    </div>
    <div>
        <img class="h-auto max-w-full rounded-lg" src="/imgs/luminosos/2.jpg" alt="">
    </div>
    <div>
        <img class="h-auto max-w-full rounded-lg" src="/imgs/luminosos/3.jpg" alt="">
    </div>
    <div>
        <img class="h-auto max-w-full rounded-lg" src="/imgs/luminosos/4.jpg" alt="">
    </div>
    <div>
        <img class="h-auto max-w-full rounded-lg" src="/imgs/luminosos/5.jpg" alt="">
    </div>
</div>



</MainLayout> 
</template>

<script setup>
import MainLayout from '~/layouts/MainLayout.vue';

</script>