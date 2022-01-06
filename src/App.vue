<template>
  <div id="app">
    <!-- <span class="bg"></span> -->
    <v-app>
      <header>
        <div>
          <Header></Header>
        </div>
      </header>

      <v-main>
        <!--  -->
        <div>
          <!-- <Main></Main> -->
          <!-- <MakeAPlan1></MakeAPlan1> -->
          <MakeAPlan2></MakeAPlan2>
        </div>

        <div>
          <!-- <Menu /> -->
          <!-- <Footer /> -->
        </div>

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
    MakeAPlan2
  },

  data: () => ({}),
};
</script>


<style lang="scss">
@import "./assets/css/style.scss";
</style>
