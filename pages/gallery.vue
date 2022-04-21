<template>
  <div>
    <div>
      <TheHeader />
    </div>
    <main class="flex flex-col min-h-screen">
      <h1
        class="
          text-center
          sm:text-3xl
          md:text-4xl
          lg:text-4xl
          font-serif
          mb-4
          mt-4
        "
      >
        Gallery
      </h1>
      <!--<pre> {{galleries.data}} </pre>-->
      <div
        class="
          container
          mx-auto
          space-y-1
          lg:space-y-0 lg:gap-2 lg:grid lg:grid-cols-3
        "
      >
        <div v-for="gallery in galleries.data" :key="gallery.id">
          <img
            :src="`http://localhost:1337${gallery.attributes.image.data.attributes.url}`"
            :alt="gallery"
          />
        </div>
      </div>
    </main>
    <TheFooter />
  </div>
</template>


<script>
import gql from 'graphql-tag'

export default {
  data(){
    return {  
     galleries:[
      
      ],
    }
  },
  apollo: {
    galleries:{
      query :gql`
     query{
  galleries{
    data {
      id,
      attributes{
       image{
          data{
            attributes{
              url
            }
          }
        }
      }
    }
  }
}`

    }
  }
}
</script>

<style scoped>
h1 {
  font-family: Lustria;
}
</style>
