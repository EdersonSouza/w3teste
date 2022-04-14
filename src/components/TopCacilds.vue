<template>
  <div class="block galleryBlock">
    <v-container>
      <h2 class="text-left">top cacilds</h2>
      <v-row>
        <v-col v-for="item in items" :key="item.id" class="d-flex child-flex mx-auto my-12" cols="12" sm="4" md="4"  height="100%" 
          max-width="374">
          <v-card flat tile class="d-flex">
            <v-img :src="item.src" aspect-ratio="1" class="white--text  align-end" 
              >
              <v-span  id="pindureta-pin" class=" mt-12" v-text="item.txt"></v-span>
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
          src: require("../assets/pindureta.png"),
          txt:"PINDURETA",
        },
        {
          id: 2,
          src: require("../assets/bolis.png"),
          txt:"BOLIS"
        },
        {
          id: 3,
          src: require("../assets/sapiens.png"),
          txt:"SAPIEN"
        },
        
      ]
      }
    },
  }
</script>
<style> 
  #pindureta-pin {
     background-color: #FF5252; 
     opacity: 0.5;
    
    

  

}
  
</style>
