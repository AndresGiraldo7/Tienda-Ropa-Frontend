<template>

    <v-content>
      <v-container>
        <v-row  class='d-flex justify-end'>
          <v-col>


  <v-treeview class='d-flex justify-end'
    rounded
    hoverable
    activatable
    :items="items"
  ></v-treeview>
  </v-col>
          
        </v-row>  
      </v-container>
    </v-content>

</template>
<script>
  export default {
    data: () => ({
      items: [
        {
          id: 1,
          name: 'Ordenar por:',
          children: [
            { id: 2, name: 'Mais recentes' },
            { id: 3, name: 'Menor preço' },
            { id: 4, name: 'Mayor preço' },
          ],
        },
      ],
    }),
  }
</script>