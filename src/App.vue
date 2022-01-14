<template>
  <v-app>
    <Header />
    <ShiftUniversity />
    <Changeworld />
    <Howtohelp />
    <IamNewHere />
    <Menu />
    <v-main>
      <slot />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer";
import Menu from "./components/Menu";
import IamNewHere from "./components/NewHere/IamNewHere.vue";
import Howtohelp from "./components/HowToHelp/Howtohelp.vue";
import Changeworld from "./components/ChangeTheWorld/Changeworld.vue";
import ShiftUniversity from "./components/ShiftUniversity/ShiftUniversity.vue";

export default {
  name: "App",

  components: {
    Menu,

    Header,
    ShiftUniversity,
    Changeworld,
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
