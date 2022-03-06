<template>
<div class="text-teal-200 bg-teal-800">
<div class="container flex items-center justify-between mx-auto">
        <h1 class="text-3xl font-thin tracking-tighter">Vue<span class="font-normal">FakeAuth</span></h1>
        <nav>
            <ul class="flex space-x-4">
                <router-link to="/">
                <li class="px-4 py-8 hover:cursor-pointer hover:bg-teal-500 hover:text-teal-800">
                    Home
                </li>
                </router-link>
                <router-link :to = "{ name: 'About'}">
                <li class="px-4 py-8 hover:cursor-pointer hover:bg-teal-500 hover:text-teal-800">About</li>
                </router-link>
                <router-link :to = "{ path: '/login', name:'Login'}">
                <li class="px-4 py-8 hover:cursor-pointer hover:bg-teal-500 hover:text-teal-800">Login</li>
                </router-link>
                <router-link :to = "{ path: '/secret', name:'Secret'}">
                <li class="px-4 py-8 hover:cursor-pointer hover:bg-teal-500 hover:text-teal-800">Secret</li>
                </router-link>
         </ul>
        </nav>
    </div>
</div>
</template>