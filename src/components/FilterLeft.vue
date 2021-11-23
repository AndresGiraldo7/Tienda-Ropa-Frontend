<template>
<v-content>
      <v-container>
<v-row>
 
  <v-col >
    <h2 class="app">Blusas</h2>
    <br/>
  <v-card
    class="left"
    width="300"
  >
    <v-list>
      <v-list-item>
        <v-list-item-icon>
          <v-icon>mdi-home</v-icon>
        </v-list-item-icon>

        <v-list-item-title class = 'app'>Filter</v-list-item-title>
      </v-list-item>

      <v-list-group
        :value="true"
        no-action
      >
          <template v-slot:activator>
            <v-list-item-content>
              <v-list-item-title class = 'app' >CORES</v-list-item-title>
            </v-list-item-content>
          </template>

          <v-list-item class = 'app'
            v-for="([title, icon], i) in admins"
            :key="i"
            link
          >
            <v-list-item-title v-text="title"></v-list-item-title>

            <v-list-item-icon>
              <v-icon v-text="icon"></v-icon>
            </v-list-item-icon>
          </v-list-item>
        </v-list-group>

        

        <v-list-group
          no-action
        >
          <template v-slot:activator>
            <v-list-item-content>
              <v-list-item-title class ="app">TAMANHOS</v-list-item-title>
            </v-list-item-content>
          </template>

          <v-list-item class = 'app'
            v-for="([title, icon], i) in cruds"
            :key="i"
            link
          >
            <v-list-item-title v-text="title"></v-list-item-title>

            <v-list-item-icon>
              <v-icon v-text="icon"></v-icon>
            </v-list-item-icon>
          </v-list-item>
        </v-list-group>

         <v-list-group
          no-action
        >

          <template v-slot:activator>
            <v-list-item-content>
              <v-list-item-title class = 'app'>FAIXA DE PRECIO</v-list-item-title>
            </v-list-item-content>
          </template>

          <v-list-item class ='app'
            v-for="([title, icon], i) in faixa"
            :key="i"
            link
          >
            <v-list-item-title v-text="title"></v-list-item-title>

            <v-list-item-icon>
              <v-icon v-text="icon"></v-icon>
            </v-list-item-icon>
          </v-list-item>
        </v-list-group>
    </v-list>
  </v-card>
</v-col>

<v-row>
<v-col>
  <br/>
  <!--1F-1C-->
  <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_2.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center" >CAMISETA MESCLA</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$28,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 3x de R$9,33</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
  <!--1F-1C-->
    <br/>
    
    
   <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_5.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">CARDIGAN OFF WHITE</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$28,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 3x de R$33,33</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>

  <!--3F-1C-->
  <br/>
     <v-card
    class="mx-auto"
    max-width="260"
    
  >
    <v-img
      class="white--text align-center"
      aling="text-center"
      height="320px"
      src="../assets/img_8.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">CROPEPED STRIPES</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$28,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 3x de R$40,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
 <!--3F-1C-->
  </v-col>
  </v-row>

  <v-row>
<v-col>
  <!--1F-2C-->
   <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_3.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">SAIA EM COURO</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$398,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 5x de R$30,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
    <br/>
   <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_6.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">BODY LEOPARDO</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$129,90</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 3x de R$43,43</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
    <br/>
   <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_9.png"
    >
    
    </v-img>
    <v-card-title class = "d-flex justify-center" >CAMISA TRASPARENTE</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$398,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 5x de R$30,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>

  </v-col>
  </v-row>

  <v-row>
<v-col>
  <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_4.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">CARDIGAN TIGRE</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$398,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 5x de R$30,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
<br/>
    <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_7.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">CARDIGAN TIGRE</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$398,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 5x de R$30,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
    <br/>
       <v-card
    class="mx-auto"
    max-width="260"
  >
    <v-img
      class="white--text align-end"
      height="320px"
      src="../assets/img_10.png"
    >
      
    </v-img>
    <v-card-title class = "d-flex justify-center">PONCHETE CLUTH</v-card-title>
    <v-card-title  class='d-flex justify-center' style="font-weight-black" >R$99,00</v-card-title>

    <v-card-text class="d-flex justify-center">
      <div>até 3x de R$33,00</div>
    </v-card-text>

    <v-card-actions  class="d-flex justify-center" >
  
      <v-btn 
        depressed
        block
        color= "black"
        class="white--text"
        >
        COMPRAR
      </v-btn>
    </v-card-actions>
  </v-card>
    

  </v-col>
  </v-row>

</v-row>

 </v-container>
    </v-content>

  
</template>

<script>
  export default {
    data: () => ({
      admins :  [
        ['Amarelo', "mdi-checkbox-blank-outline" ],
        ['Azul', 'mdi-checkbox-outline'],
        ['Branco', "mdi-checkbox-blank-outline" ],
        ['Cinza', "mdi-checkbox-blank-outline" ],
        ['Laranja', "mdi-checkbox-blank-outline" ],
        ['Verde', "mdi-checkbox-blank-outline" ],
        ['Vermelho', "mdi-checkbox-blank-outline" ],
        ['Preto', "mdi-checkbox-blank-outline" ],
        ['Rosa', "mdi-checkbox-blank-outline" ],
        ['Vintho', "mdi-checkbox-blank-outline" ],
      ],
      cruds: [
        ['P','mdi-checkbox-outline' ],
        ['M', 'mdi-checkbox-blank-outline'],
        ['G', 'mdi-checkbox-blank-outline'],
        ['U', 'mdi-checkbox-blank-outline'],
        ['36', 'mdi-checkbox-blank-outline'],
        ['38', 'mdi-checkbox-blank-outline'],
        ['40', 'mdi-checkbox-blank-outline'],
        ['42', 'mdi-checkbox-blank-outline'],
        ['44', 'mdi-checkbox-blank-outline'],
        ['46', 'mdi-checkbox-blank-outline'],
      ],

      faixa: [
        ['de R$ O até R %50','mdi-checkbox-outline' ],
        ['de R$ 51 até R %150', 'mdi-checkbox-blank-outline'],
        ['de R$ 151 até R %300', 'mdi-checkbox-blank-outline'],
        ['de R$ 301 até R %500', 'mdi-checkbox-blank-outline'],
        ['a partir de R$ 501', 'mdi-checkbox-blank-outline'],

      ]
    }),
  }
</script>





<style lang ="scss">
.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
.nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #0e104e;

    &.router-link-exact-active {
      color: #0b1786;
    }
  }
}
</style>