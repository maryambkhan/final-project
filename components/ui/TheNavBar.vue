<template>
  <div class="sm:flex sm:justify-center">
    <div class="sm:hidden mt-2">
      <button @click="isOpen = !isOpen" type="button" class="hover:text-slate-600">
        <span class="font-semibold">Menu</span>
      </button>
    </div>
    
    <div :class="isOpen ? 'block' : 'hidden'" class="items-center px-2 pt-2 pb-4 sm:flex">
    <NuxtLink to="/" class="block px-2 py-1 text-lg font-semibold rounded hover:bg-gray-300">HOME</NuxtLink>
    <NuxtLink to="/gallery" class="block  px-2 py-1 text-lg font-semibold rounded hover:bg-gray-300">GALLERY</NuxtLink>
    <NuxtLink  to="/about" class="block   px-2 py-1 text-lg font-semibold rounded hover:bg-gray-300" >ABOUT</NuxtLink>
    <NuxtLink to="/contact" class="block px-2 py-1  text-lg font-semibold rounded hover:bg-gray-300">CONTACT</NuxtLink>
  </div>
  </div>
</template>


<script setup>
export default {
    data() {
      return {
        isOpen: false,
      };
    },
  };
</script>

