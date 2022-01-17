<template>
  <v-app>
    <Header />
    <!-- <ShiftUniversity />
    <Changeworld />
    <Howtohelp />
    <IamNewHere />
    <Menu /> -->
    <ShiftUniversityInsidePage />
    <v-main>
      <slot />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer";
// import Menu from "./components/Menu";
// import IamNewHere from "./components/NewHere/IamNewHere.vue";
// import Howtohelp from "./components/HowToHelp/Howtohelp.vue";
// import Changeworld from "./components/ChangeTheWorld/Changeworld.vue";
// import ShiftUniversity from "./components/ShiftUniversity/ShiftUniversity.vue";
import ShiftUniversityInsidePage from "./components/ShiftUniversityInside/ShiftUniversityInsidePage.vue";

export default {
  name: "App",

  components: {
    Footer,
    Header,
    // ShiftUniversity,
    // Menu,
    // Changeworld,

    // IamNewHere,
    // Howtohelp,
    ShiftUniversityInsidePage,
  },

  data: () => ({ drawer: false }),
};
</script>
<style lang="scss">
@import "./assets/css/style.scss";
</style>
