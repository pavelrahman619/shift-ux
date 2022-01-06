<template>
  <v-app>
    <v-card class="overflow-hidden">
      <v-app-bar absolute color="white" elevate-on-scroll elevation="4">
        <v-toolbar-side-icon>
          <v-img class="mr-3" src="@/assets/l1.png" height="50px" width="150px"> </v-img>
        </v-toolbar-side-icon>

        <v-spacer></v-spacer>
        <v-app-bar-nav-icon> </v-app-bar-nav-icon>
      </v-app-bar>
      <v-sheet id="scrolling-techniques-7" max-height="80">
        <v-container style="height: 150px"> </v-container>
      </v-sheet>
    </v-card>

    <v-main>
      <IamNewHere />
      <Howtohelp />
      <!-- <Menu /> -->
      <Footer />
    </v-main>
  </v-app>

</template>

<script>
import Footer from "./components/Footer";
// import Menu from "./components/Menu";
import IamNewHere from "./components/NewHere/IamNewHere.vue";
import Howtohelp from "./components/HowToHelp/Howtohelp.vue";

export default {
  name: "App",

  components: {
    // Menu,
    Footer,
    IamNewHere,
    Howtohelp,
  },

  data: () => ({ drawer: false }),
};
</script>
<style lang="scss">
@import "./assets/css/style.scss";
</style>