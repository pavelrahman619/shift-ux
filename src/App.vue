<template>
  <div id="app">
    <!-- <span class="bg"></span> -->
    <v-app>
      <Header></Header>
      <v-main>
        <!-- Provides the application the proper gutter -->
        <v-container fluid>
          <!--  -->
          <!-- <Main></Main> -->
          <!-- <MakeAPlan1></MakeAPlan1> -->
          <MakeAPlan2></MakeAPlan2>
          <!-- <Menu /> -->
          <!-- <Footer /> -->
        </v-container>
      </v-main>
    </v-app>
  </div>
</template>


<script>
import Header from "./components/Header";
// import Main from "./components/Main";
// import Footer from "./components/Footer";
// import MakeAPlan1 from "./components/MakeAPlan1";
import MakeAPlan2 from "./components/MakeAPlan2";

export default {
  name: "App",

  components: {
    Header,
    // Main,
    // Footer,
    // MakeAPlan1,
    MakeAPlan2,
  },

  data: () => ({}),
};
</script>


<style lang="scss">
@import "./assets/css/style.scss";
</style>
