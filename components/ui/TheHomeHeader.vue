<template>
<div>
  <h1 class="font-serif text-4xl ml-2 text-white flex justify-end pt-56 pr-52 mr-12">ABK Photos</h1>
  <div class="flex justify-end gap-6 mr-12 mt-5 pr-32">
    <NuxtLink to="/gallery" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-gray-500">GALLERY</NuxtLink>
    <NuxtLink  to="/about" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-gray-500" >ABOUT</NuxtLink>
    <NuxtLink to="/contact" class="text-white block  px-2 py-1 text-xl font-semibold rounded hover:bg-gray-500">CONTACT</NuxtLink>
  </div>
   <section class="flex justify-end  text-white mr-5 mt-6 pr-72 gap-5">
     <a href="https://www.instagram.com/_abkphotos/"> <font-awesome-icon :icon="['fab', 'instagram']" class="mr-2 text-3xl rounded hover:text-4xl" /></a>
     <a href="https://www.facebook.com/atikabk"> <font-awesome-icon :icon="['fab', 'facebook']"  class="mr-2 text-3xl rounded hover:text-4xl"/></a>
  
    </section>
  </div>
</template>


<style scoped>
h1{
  
  text-shadow: 1px 1px 2px black, 0 0 1em gray, 0 0 0.2em gray;
  font: 1.5em Georgia;
  font-size: 40px;

}
</style>


<script setup>
</script>
