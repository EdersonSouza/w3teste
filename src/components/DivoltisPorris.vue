<template>
  
  <v-div class="block galleryBlock">
    <v-container>

      <v-card
  
            
        >
        <h2 class="text-left">top cacilds</h2>
        <v-col></v-col>
        <v-container>

            <v-row >
                <v-col  class="d-flex child-flex mx-auto " cols="12"
                md="7"
                offset-md="5"  height="100%" max-width="374"
                >
                    <v-card >
                        <v-img
                            src="../assets/divoltis/mussum.png"
                        ></v-img>

                        <v-card-title class="primary--text">Consentis</v-card-title>
                        <v-card-text class="black--text">
                                <v-p>Manduma pindureta quium dia nois paga</v-p> 
                                <v-spacer></v-spacer>
                                <v-p> Sapien in monti palavri</v-p>
                                        
                        </v-card-text>

                    </v-card>
                    <v-spacer></v-spacer>

                    <v-card >
                        <v-img
                            src="../assets/divoltis/divoltis_porris-02.png"
                        ></v-img>

                        <v-card-title class="primary--text">Consentis</v-card-title>
                        <v-card-text class="black--text">
                                <v-p>Manduma pindureta quium dia nois paga</v-p> 
                                <v-spacer></v-spacer>
                                <v-p> Sapien in monti palavri</v-p>
                                        
                        </v-card-text>

                    </v-card>
                    
                </v-col>
                <v-col  class="d-flex child-flex mx-auto " cols="12"
                md="7"
                offset-md="5" height="100%" max-width="374"
                >
                    <v-card >
                        <v-img
                            src="../assets/divoltis/divoltis_porris-03.png"
                        ></v-img>

                        <v-card-title class="primary--text">Consentis</v-card-title>
                        <v-card-text class="black--text">
                                <v-p>Manduma pindureta quium dia nois paga</v-p> 
                                <v-spacer></v-spacer>
                                <v-p> Sapien in monti palavri</v-p>
                                        
                        </v-card-text>

                    </v-card>
                    <v-spacer></v-spacer>

                    <v-card >
                        <v-img
                            src="../assets/divoltis/divoltis_porris-04.png"
                        ></v-img>

                        <v-card-title class="primary--text">Consentis</v-card-title>
                        <v-card-text class="black--text">
                                <v-p>Manduma pindureta quium dia nois paga</v-p> 
                                <v-spacer></v-spacer>
                                <v-p> Sapien in monti palavri</v-p>
                                        
                        </v-card-text>

                    </v-card>
                    
                </v-col>
                

            </v-row>

        </v-container>
        
        
            
            
            
            
        </v-card>
        <v-container>
            <v-row>
                    <v-card >
                        <v-img
                            src="../assets/divoltis/propaganda.png"
                        ></v-img>


                    </v-card>

              

            </v-row>

        </v-container>
     
    </v-container>
    
    
  </v-div>
  
  
  
  
</template>
<script>


export default{

    name: 'DivoltisPorris',

    data () {
        return{

        cards: [
            { title: 'Pre-fab homes', src: 'https://cdn.vuetifyjs.com/images/cards/house.jpg', flex: 12 },
            { title: 'Favorite road trips', src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 6 },
            { title: 'Best airlines', src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 6 },
        ],

        }

    }
    
}
</script>
