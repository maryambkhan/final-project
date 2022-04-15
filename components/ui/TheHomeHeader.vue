<template>
<div class="">
  <h1 class="font-serif text-4xl ml-2 text-white flex justify-end pt-72 pr-52 mr-12">ABK Photos</h1>
  <div class="flex justify-end gap-6 mr-12 mt-5 pr-32">
    <NuxtLink to="/gallery" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-red-300">GALLERY</NuxtLink>
    <NuxtLink  to="/about" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-red-300" >ABOUT</NuxtLink>
    <NuxtLink to="/contact" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-red-300">CONTACT</NuxtLink>
  </div>
   <section class="flex justify-end  text-white mr-5 mt-6 pr-72 gap-5">
     <a href="https://www.instagram.com/_abkphotos/"> <font-awesome-icon :icon="['fab', 'instagram']" class="mr-2 text-3xl rounded hover:text-4xl" /></a>
     <a href="https://www.facebook.com/atikabk"> <font-awesome-icon :icon="['fab', 'facebook']"  class="mr-2 text-3xl rounded hover:text-4xl"/></a>
  
    </section>
  </div>
</template>

<style scoped>
  
</style>

<script setup>


</script>
