<template>
  <div id="app">
    <!-- <span class="bg"></span> -->
    <v-app id="main-content">
      <Header></Header>

      

      <!-- Sizes your content based upon application components -->
      <v-main >
        <!-- Provides the application the proper gutter -->
        <!-- <v-container fluid> -->

          <!--  -->
          <!-- <Main></Main> -->
          <!-- <MakeAPlan1></MakeAPlan1> -->
          <!-- <MakeAPlan2></MakeAPlan2> -->
          <!-- <MakeAPlan3></MakeAPlan3> -->
          <!-- <MakeAPlan31></MakeAPlan31> -->
          <MakeAPlanHover></MakeAPlanHover>
          <!-- <Menu /> -->
        <!-- </v-container> -->
      </v-main>
          <Footer></Footer>
    </v-app>
  </div>
</template>


<script>
import Header from "./components/Header";
// import Main from "./components/Main";
// import MakeAPlan1 from "./components/MakeAPlan1";
// import MakeAPlan2 from "./components/MakeAPlan2";
// import MakeAPlan3 from "./components/MakeAPlan3";
// import MakeAPlan31 from "./components/MakeAPlan31";
import MakeAPlanHover from "./components/MakeAPlan/MakeAPlanHover";
import Footer from "./components/Footer";

export default {
  name: "App",

  components: {
    Header,
    // Main,
    // MakeAPlan1,
    // MakeAPlan2,
    // MakeAPlan3,
    // MakeAPlan31,
    MakeAPlanHover,
    Footer,
  },

  data: () => ({}),
};
</script>


<style lang="scss">
@import "./assets/css/style.scss";
</style>
