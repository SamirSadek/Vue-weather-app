<template>
    <header class="sticky top-0 bg-primary shadow-lg">
        <nav class="container flex flex-col sm:flex-row items-center gap-4 text-white py-6">
            <RouterLink :to="{ name: 'home' }">
                <div class="flex items-center gap-3 flex-1">
                    <i class="fa-solid fa-sun text-2xl"></i>
                    <p class="text-2xl">Local Weather</p>
                </div>
            </RouterLink>

            <div class="flex gap-3 flex-1 justify-end">
                <i class="fa-solid fa-circle-info text-xl hover:text-gray-700 duration-150 cursor-pointer"></i>
                <i class="fa-solid fa-plus text-xl hover:text-gray-700 duration-150 cursor-pointer"></i>
            </div>

        </nav>
    </header>
</template>

<script setup>
import { RouterLink } from 'vue-router';
</script>

