<template>
  <div id="app">
    <span class="bg"></span>
    <v-app>
      <v-navigation-drawer app right hide-overlay="true" v-model="drawer" width="100%">
        <!--  -->
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
        <Menu></Menu>
      </v-navigation-drawer>

      <v-app-bar app color="transparent">
        <a href="#">
          <img
            class="mr-3"
            :src="require('./assets/images/shift-logo.png')"
            height="40"
        /></a>

        <v-app-bar-nav-icon  @click="drawer = !drawer"></v-app-bar-nav-icon>
      </v-app-bar>

      <v-main>
        <!--  -->
        <div>
          <Main></Main>
        </div>
        

        <div>
          <!-- <Menu /> -->
          <Footer /> 
        </div>
      </v-main>
    </v-app>
  </div>
</template>


<script>
import Main from "./components/Main";
import Menu from "./components/Menu";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Main,
    Menu,
    Footer,
  },

  data: () => ({ drawer: false }),
};
</script>


<style lang="scss">
@import "./assets/css/style.scss";
</style>