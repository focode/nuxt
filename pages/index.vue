<template>
<div>
<v-content>
  <section>
        <v-layout
          column
          wrap
          class="my-5"
          align-center
        >
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline">The best way to start developing</h2>
              <span class="subheading">
                Cras facilisis mi vitae nunc
              </span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card flat class="transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="red--text text--lighten-2">color_lens</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Material Design</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card flat class="transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="red--text text--lighten-2">flash_on</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Fast development</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card flat class="transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="red--text text--lighten-2">build</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Completely Open Sourced</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>
</v-content> 
  
 <v-container >

  <v-layout >
    <v-flex sm4 >
  <cards></cards>
    </v-flex>   
    <v-flex sm4 offset-sm1>
  <cards></cards>
    </v-flex>
<v-flex sm4 offset-sm1>
  <cards></cards>
    </v-flex>
  </v-layout>
 <p></p>
  <p></p>
  <v-layout >
    <v-flex sm4 >
  <cards></cards>
    </v-flex>   
    <v-flex sm4 offset-sm1>
  <cards></cards>
    </v-flex>
<v-flex sm4 offset-sm1>
  <cards></cards>
    </v-flex>
  </v-layout>
 </v-container>
  </div>
</template>


<script>
import cards from '../components/cards'
export default {
  components: {
    cards
  }
}
</script>

<style scoped>
.grid { 
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  grid-gap: 2vw;
  }
.grid > div {
  font-size: 5vw;
  padding: .5em;
  background: gold;
  text-align: center;
}

</style>


