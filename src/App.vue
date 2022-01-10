<template>
  <v-app>
    <v-main>
      <Header />
      <Changeworld />
      <!-- <IamNewHere />  -->
     <!-- <Howtohelp />  -->
      <!-- <Menu /> -->
      <Footer />
    </v-main>
  </v-app>

</template>

<script>





import Header from "./components/Header.vue";
import Footer from "./components/Footer";
// import Menu from "./components/Menu";
// import IamNewHere from "./components/NewHere/IamNewHere.vue";
// import Howtohelp from "./components/HowToHelp/Howtohelp.vue";
import Changeworld from "./components/ChangeTheWorld/Changeworld.vue";

export default {
  name: "App",

  components: {
    // Menu,
    Header,
    Changeworld,
    Footer,
    // IamNewHere,
    // Howtohelp,
    
  },

  data: () => ({ drawer: false }),
};
</script>
<style lang="scss">
@import "./assets/css/style.scss";
</style>