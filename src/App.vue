<template>
  <v-app>
    <div>
        <v-toolbar
         color="primary"
          dark
          prominent
          
        >
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
          <v-spacer></v-spacer>
          <v-spacer></v-spacer>
          <v-logo
            >
            <v-img
            align="center"
            width="70%"
            src="@/assets/agencia-logo.png"
            >
              
            </v-img>
          </v-logo>

          <v-spacer></v-spacer>
          <v-row warap>
            <v-col sm6 md6>
              <v-btn icon >
                <v-icon>mdi-facebook</v-icon>
                Curtir
              </v-btn>
            </v-col> 
            <v-col sm6 md6>
              <v-btn icon >
                <v-icon>mdi-instagram</v-icon>
                Seguir
              </v-btn>
            </v-col>
          </v-row>

          
         
        </v-toolbar>
      </div>
    <v-spacer></v-spacer>
    <v-spacer></v-spacer>
    <v-main>
      <Teste/>
      <top-cacilds/>
      <divoltis-porris/>
      <pais-filhis/>
      
    </v-main>
    
     <footerr/>
      
    
    

  </v-app>
</template>

<script>
import Teste from './components/Teste';
import TopCacilds from './components/TopCacilds';
import DivoltisPorris from './components/DivoltisPorris.vue';
import PaisFilhis from'./components/PaisFilhis.vue'
import Footerr from'./components/Footer.vue'

export default {
  name: 'App',

  components: {
    Teste,
    TopCacilds,
    DivoltisPorris,
    PaisFilhis,
    Footerr,
  },

  data: () => ({
    //
  }),
};
</script>
