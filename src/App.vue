<template>
  <div class="text-center m-6">
    <nav>
    <router-link class="text-xl font-thin shadow-lg rounded-md p-2 m-4 ring-4 ring-gray-600 ring-opacity-30 bg-green-600 bg-opacity-40 hover:bg-transparent" to="/">Home</router-link> 
    <router-link class="text-xl font-thin shadow-lg rounded-md p-2 m-4 ring-4 ring-gray-600 ring-opacity-30 bg-green-600 bg-opacity-40 hover:bg-transparent" to="/about">About</router-link> 
    <router-link class="text-xl font-thin shadow-lg rounded-md p-2 m-4 ring-4 ring-gray-600 ring-opacity-30 bg-green-600 bg-opacity-40 hover:bg-transparent" to="/contact">Contact</router-link> 
    <router-link class="text-xl font-thin shadow-lg rounded-md p-2 m-4 ring-4 ring-gray-600 ring-opacity-30 bg-green-600 bg-opacity-40 hover:bg-transparent" to="/hobbies">Hobbies</router-link>
  </nav>
  </div>
  <router-view />
</template>

<script setup></script>
