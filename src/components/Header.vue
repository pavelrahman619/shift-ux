<template>
  <div>
    <v-navigation-drawer
      app
      right
      hide-overlay="true"
      v-model="drawer"
      width="100%"
      height="100%"
      absolute
    >
      <!--  -->
      <!-- <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon> -->
      <Menu></Menu>
    </v-navigation-drawer>

    <v-app-bar app color="yellow">
      <a href="#">
        <img
          class="mr-3"
          :src="require('../assets/images/shift-logo.png')"
          height="40"
      /></a>

      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    </v-app-bar>
  </div>
</template>

<script>
import Menu from "./Menu";

export default {
    name: "Header",

    components: {
    Menu,
  },
  data: () => ({ drawer: false }),

};
</script>

<style lang="scss">

</style>