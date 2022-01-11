<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <v-app >
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
          <!-- <Menu /> -->
        <!-- </v-container> -->
      </v-main>
          <Footer></Footer>
    </v-app>
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/Header";
// import Main from "./components/Main";
// import MakeAPlan1 from "./components/MakeAPlan1";
// import MakeAPlan2 from "./components/MakeAPlan2";
// import MakeAPlan3 from "./components/MakeAPlan3";
// import MakeAPlan31 from "./components/MakeAPlan31";
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
    Footer,
  },

  data: () => ({}),
};
</script>


<style lang="scss">
@import "./assets/css/style.scss";
</style>