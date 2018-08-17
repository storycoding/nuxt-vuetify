<template>
  <v-app dark>
    <section class="container">
      <div>
        <v-btn color="info">Info</v-btn>
        <v-btn color="primary">Primary</v-btn>
        <app-logo/>

        <v-container>
          <v-layout row wrap>
            <v-flex xs1>
              <v-card dark color="primary">
                <v-card-text class="px-0">v-card</v-card-text>
              </v-card>
              <v-card dark color="primary">
                <v-card-text class="px-0">v-card</v-card-text>
              </v-card>
              <v-card dark color="primary">
                <v-card-text class="px-0">v-card</v-card-text>
              </v-card>
              <v-card dark color="primary">
                <v-card-text class="px-0">v-card</v-card-text>
              </v-card>
              <v-card dark color="primary">
                <v-card-text class="px-0">v-card</v-card-text>
              </v-card>
              <div class="square">orange</div>
              <div class="square">orange</div>
              <div class="square">orange</div>
            </v-flex>
          </v-layout>

    <v-layout row wrap>
      <v-flex xs12>
        <v-card dark color="error">
          <v-card-text class="px-0 m-2">12</v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 2" :key="`6${i}`" xs6>
        <v-card dark color="secondary">
          <v-card-text class="px-0 m-2">6</v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 3" :key="`4${i}`" xs4>
        <v-card dark color="error">
          <v-card-text class="px-0 m-2">4</v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 4" :key="`3${i}`" xs3>
        <v-card dark color="secondary">
          <v-card-text class="px-0 m-2">3</v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 6" :key="`2${i}`" xs2 m-2 p-2>
        <v-card dark color="error">
          <v-card-text class="px-0 m-2">2</v-card-text>
        </v-card>
      </v-flex>
      <v-flex v-for="i in 12" :key="`1${i}`" xs1>
        <v-card dark color="secondary">
          <v-card-text class="px-0 m-2">1</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>


        </v-container>

        <h1 class="title">
          nuxt-vuetify
        </h1>
        <h2 class="subtitle">
          Nuxt.js project
        </h2>
        <div class="links">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            class="button--green">Documentation</a>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            class="button--grey">GitHub</a>
        </div>
      </div>
    </section>
  </v-app>
</template>
<v-app>
<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>

* {
  width: 200px:
  height: 200px;
  color: #FF5252;
  background-color: orange;
  border-radius: 10px;
}
</style>

