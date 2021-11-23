<template>

    <v-content>
      <v-container>
        <v-row >
          <v-col>
            <br/>
            <v-img 
                    max-height="200px" 
                    max-width="200px"
                    src= "../assets/logo-m3.png"
                    alaign="left"
                   ></v-img>
      
    
              <br/>
              <br/>
              <br/>
          </v-col>
          
    <v-col class='d-flex justify-end'>
    <v-btn 
      fab
      dark
      small
    >
      <v-icon dark>
        mdi-cart
      </v-icon>
    </v-btn>
      </v-col>
        </v-row>  
          </v-container>
             </v-content>

</template>

<script>
export default {
    data: () => {
        return {
            items:
            {
src : require ('../assets/logo-m3.png')
            }
        
            
    }

}
}
</script>

<style>

</style>