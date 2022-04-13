<template>
  <div class="block galleryBlock">
    <v-container>
      <h2 class="text-left">top cacilds</h2>
      <v-row>
        <v-col v-for="item in items" :key="item.id" class="d-flex child-flex mx-auto my-12" cols="12" sm="4" md="4"  height="100%" 
          max-width="374">
          <v-card flat tile class="d-flex">
            <v-img :src="item.src" aspect-ratio="1" class="grey lighten-2">
              
            </v-img>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
  
</template>
<script>
  
  export default {
    name: 'TopCacilds',

   data () {
      return {
        
        items: [
        {
          id: 1,
          src: require("../assets/pindureta.png")
        },
        {
          id: 2,
          src: require("../assets/bolis.png")
        },
        {
          id: 3,
          src: require("../assets/sapiens.png")
        },
        
      ]
      }
    },
  }
</script>
