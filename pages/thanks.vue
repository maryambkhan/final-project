<template>
 <div class="max-h-full h-[100vh] bg-center" :style="{ backgroundImage: `url(${backgroundUrl})` }" >
  <div class="text-center">
    <h1 class="flex justify-center font-serif text-6xl text-white pt-44">THANK YOU!</h1>
		<button type="submit" id="submit" class="text-blue-300 underline hover:text-blue-500 text-2xl"><a href="gallery">Go Back </a>
</button>
  </div>
 </div>
</template>

<script setup>
import backgroundUrl from '/assets/images/thanks.jpg'
export default {
  data() {
    return { backgroundUrl }
  }
}
</script>