<template>
  <!-- <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app> -->

  <div id="app">
    <span class="bg"></span>
    <v-app>
      <v-navigation-drawer right hide-overlay="true" v-model="drawer" app>
        <!--  -->
      </v-navigation-drawer>

      <v-app-bar app color="transparent">
        <a href="#">
          <img
            class="mr-3"
            :src="require('../public/images/shift-logo.png')"
            height="40"
        /></a>

        <!-- <v-toolbar-title>Application</v-toolbar-title> -->
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      </v-app-bar>

      <v-main>
        <!--  -->
        <div class="container">
          <div>
            <h1><b>Let's change the world one campaign at a time</b></h1>
          </div>

          <div class="main-list">
            <v-list-item>
              <v-list-item-content>
                <a href="#"
                  ><v-list-item-title class="pink--text"
                    >I am new here</v-list-item-title
                  ></a
                >
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <a href="#"
                  ><v-list-item-title class="pink--text"
                    >I want to change the world</v-list-item-title
                  ></a
                >
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <a href="#"
                  ><v-list-item-title class="pink--text"
                    >I want to know how to help</v-list-item-title
                  ></a
                >
              </v-list-item-content>
            </v-list-item>
          </div>

          <div class="buttons">
            <img :src="require('../public/images/button1.png')" />
            <img :src="require('../public/images/button2.png')" />
          </div>
        </div>
      </v-main>
    </v-app>
  </div>
</template>


<script>
// import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {
    // HelloWorld,
  },

  data: () => ({ drawer: false }),
};
</script>


<style lang="scss">
@import './assets/css/style.scss';

</style>