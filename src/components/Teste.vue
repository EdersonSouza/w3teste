<template>
  <v-div>
    <v-container>
      <v-flex xs12 sm12 md12>
        <v-card class="align-center justify-space-between mr-0 sx4 md4 sm4 lg4 xl4 "  >
          <v-carousel>
            <v-carousel-item
              src="../assets/image_rotate.png"
              width="100%"
              
            >

              <v-row
              align="end"
              class="fill-height"
            >
              <v-col
                align-self="start"
                class="pa-0"
                cols="12"
              >
                  </v-col>
                  <v-col class="py-0">
                    <v-list-item
                      color="rgba(0, 0, 0, .4)"
                      dark
                    >
                      <v-list-item-content>
                        <v-list-item-title id ="mussum" class="text-h8">
                          MUSSUM IPSUM CACILDS
                        </v-list-item-title>
                        <v-list-item-title class="text-h5">Pra lá, depois divoltis porris.</v-list-item-title>
                        <v-list-item-title class="text-h6">Paisis, filhis, espiritis Santis.</v-list-item-title>
                      </v-list-item-content>
                    </v-list-item>
                  </v-col>
                </v-row>
              
            </v-carousel-item>
            <v-carousel-item
              src="../assets/lobo.jpg"
              
            >
              
            </v-carousel-item>
            <v-carousel-item
              src="../assets/image_rotate.png"
              
            >
              
            </v-carousel-item>
            
            
          </v-carousel>
        </v-card>

      </v-flex>

    </v-container>
    
    
  </v-div>
  
</template>
<script>
  
  export default {
    name: 'Teste',

   data () {
      return {
        items: [
          {
            src:'../assets/logo.png',
            text:'ola mundo'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
  }
</script>
<style >
  #mussum {
    max-width: 20%;
    background-color: #2c8ccc;
   
  }
</style>
