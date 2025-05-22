<template>
    <nav
        class="fixed top-0 left-0 right-0 bg-white border-b shadow-sm px-4 py-2 flex items-center justify-between z-50">
        <!-- Left: Logo -->
        <div class="flex items-center space-x-2">
            <img src="https://cdn.freebiesupply.com/logos/large/2x/facebook-logo-2019.png" alt="Logo"
                class="w-10 h-10" />
            <span class="text-blue-600 text-xl font-bold">Portfolio</span>
        </div>

        <!-- Center: Navigation Links -->
        <div class="hidden md:flex space-x-6 text-gray-600 text-sm font-medium">
            <RouterLink to="/" class="hover:text-blue-600 transition">Home</RouterLink>
            <RouterLink to="/friends" class="hover:text-blue-600 transition">Projects</RouterLink>
            <RouterLink to="/watch" class="hover:text-blue-600 transition">About</RouterLink>
            <RouterLink to="/marketplace" class="hover:text-blue-600 transition">Contact</RouterLink>
        </div>

        <!-- Right: Search and Profile -->
        <div class="flex items-center space-x-4">
            <input type="text" placeholder="Search Facebook"
                class="hidden md:block px-3 py-1.5 bg-gray-100 rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
            <img src="https://scontent.fceb1-4.fna.fbcdn.net/v/t39.30808-6/497752133_2525215041150324_3284023876862007287_n.jpg"
                alt="Profile" class="w-8 h-8 rounded-full border border-gray-300" />
        </div>
    </nav>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>