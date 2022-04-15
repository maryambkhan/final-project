<template>
  <div class="max-h-full h-[100vh] bg-center" :style="{ backgroundImage: `url(${backgroundUrl})` }" >
   
   <TheHomeHeader />
  </div>
</template>

<script>
import backgroundUrl from '/assets/images/hero.jpg'
export default {
  data() {
    return { backgroundUrl }
  }
}
</script>
