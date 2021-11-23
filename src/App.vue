<template>
<v-app>


    
    <Header/>
    <FilterRight/>
    <FilterLeft/>
    
    

</v-app>

  
  
 
</template>

<script>

import Header from '@/components/Header.vue'
import FilterRight from '@/components/FilterRight.vue'
import FilterLeft from '@/components/FilterLeft.vue'


export default {
  name: 'App',

  components: {
   

    Header,
    FilterRight,
    FilterLeft,
    
    
   
    
  },

  data: () => ({
    //
  }),
};
</script>
