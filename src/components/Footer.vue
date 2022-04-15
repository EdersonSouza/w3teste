<template>
    <div>
        <div>
            <v-toolbar
            color="primary "
            dark
            >
            </v-toolbar>
        </div>
        <div>
        
            <v-toolbar
            color="#2d3e57"
            prominent
            
            >
            
                <v-card-text class="text-h16 white--text" >
                        <v-span>2022- TODOS OS DIRETOS RESERVADOS</v-span>
                        <v-spacer></v-spacer>
                        <v-span>AS NOTÍCIAS VINCULADAS NO PORTAL SÃO DE INTERIA RESPONSABILIDADES DE SEUS AUTORES</v-span>
                                            

                    </v-card-text>
                <v-spacer></v-spacer>
                
                <v-span id="ag">
                    <v-logo
                            >
                            <v-img
                            align="left"
                            width="100%"
                            src="../assets/agencia-logo.png"
                            >
                            
                            </v-img>
                        </v-logo>
                </v-span>
            

            </v-toolbar>
        </div>     
    </div>
</template>
<script>


export default{
    name:'Footerr',

   data (){

   }
}
</script>
<style>
    #ag {
     
     max-width: 10%;
     margin:5% 0%;
     

  

}
</style>