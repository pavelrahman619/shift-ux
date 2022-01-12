<template>
  <v-container class="yellow" fluid fill-height1>
    <row class="main-head-text">
      <h1 class="text-center">
        <b>Let's change the world one campaign at a time</b>
      </h1>
    </row>

    <MainMobile />

    <div class="main-list">
      <v-flex shrink>
        <v-list-item v-for="item in items" :key="item">
          <!-- <v-spacer></v-spacer> 
        <v-spacer></v-spacer>  -->
          <v-list-item-content>
            <a href="#"
              ><v-list-item-title class="pink--text text-left">{{
                item
              }}</v-list-item-title></a
            >
          </v-list-item-content>
        </v-list-item>
      </v-flex>
    </div>

    <div class="buttons-list">
      <!-- <a href=""><img :src="require('../assets/images/button1.png')" /></a> 
      <a href=""><img :src="require('../assets/images/button2.png')" /></a>  -->
      <a href="">
        <div class="rectangle">
          <div class="circle"></div>
          <b><p class="button-list-count">5</p></b>
        </div></a
      >
      <a href=""
        ><div class="circle">
          <v-icon color="white" size="20px">mdi-chat-processing-outline</v-icon>
        </div></a
      >
    </div>
  </v-container>
</template>

<script>
import mainListItems from "../mixins/mainListItems";
import MainMobile from "./MainMobile";
export default {
  name: "Main",
  // data: function () {
  //   return {
  //     items: [
  //       "I am new here",
  //       "I want to change the world",
  //       "I want to know how to help",
  //     ],
  //   };
  // },
  components: {
    MainMobile,
  },
  mixins: [mainListItems],
};
</script>

<style lang="scss">
</style>