<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >

      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-spacer></v-spacer>
    </v-app-bar>
    <v-spacer></v-spacer>
    <v-spacer></v-spacer>
    <v-main>
      <Teste/>
    </v-main>
    
    <v-div>
      <top-cacilds/>
    </v-div>
    

  </v-app>
</template>

<script>
import Teste from './components/Teste';
import TopCacilds from './components/TopCacilds';

export default {
  name: 'App',

  components: {
    Teste,
    TopCacilds
  },

  data: () => ({
    //
  }),
};
</script>
