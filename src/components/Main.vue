<template>
  <v-container class="yellow" fluid fill-height1>
    <!-- TOP SECTION -->

    <v-row>
      <v-col lg="3" class="d-flex align-end">
        <div class="main-shape-1"></div>
      </v-col>

      <v-col lg="3" class="d-flex space-between">
        <v-row class="ma-2">
          <v-row class="justify-center">
            <div class="main-shape-2"></div>
          </v-row>
          <v-row class="justify-center">
            <v-card width="50%" rounded>
              <v-img src="@/assets/images/homepage/1.png" height="auto">
              </v-img>
            </v-card>
          </v-row>
        </v-row>
      </v-col>

      <v-col lg="3">
        <v-card width="80%" rounded>
          <v-img src="@/assets/images/homepage/2.png" height="auto"> </v-img>
        </v-card>
      </v-col>

      <v-col lg="1" class="d-flex align-end">
        <v-card width="80%" rounded>
          <v-img src="@/assets/images/homepage/3.png" height="auto"> </v-img>
        </v-card>
      </v-col>

      <v-col lg="2" class="d-flex align-end">
        <div class="main-shape-3"></div>
      </v-col>
    </v-row>

    <!-- MID SECTION -->

    <v-row class="main-head-text justify-center">
      <h1 class="text-center">
        <b>Let's change the world one campaign at a time</b>
      </h1>
    </v-row>

    <!-- BOTTOM SECTION -->

    <v-row>
      <v-col lg="2" class="d-flex align-end justify-end">
        <v-card width="40%" rounded>
          <v-img src="@/assets/images/homepage/4.png" height="auto"> </v-img>
        </v-card>
      </v-col>

      <v-col lg="3" class="d-flex space-between">
        <v-row class="ma-2">
          <v-row class="justify-center">
            <v-card width="50%" rounded>
              <v-img src="@/assets/images/homepage/5.png" height="auto">
              </v-img>
            </v-card>
          </v-row>
          <v-row class="justify-center align-end">
            <div class="main-shape-4"></div>
          </v-row>
        </v-row>
      </v-col>

      <v-col lg="3" class="d-flex space-between">
        <v-row class="ma-2">
          <v-row>
            <v-sheet
              v-for="i in 4"
              :key="i"
              class="circle-empty-main"
            ></v-sheet>
          </v-row>
          <v-row>
            <v-card width="50%" rounded>
              <v-img src="@/assets/images/homepage/6.png" height="auto">
              </v-img>
            </v-card>
          </v-row>
        </v-row>
      </v-col>

      <!-- LINKS -->

      <v-col lg="4">
        <v-row>
          <v-list-item v-for="item in items" :key="item">
            <v-list-item-content>
              <a href="#"
                ><v-list-item-title class="pink--text text-left">{{
                  item
                }}</v-list-item-title></a
              >
            </v-list-item-content>
          </v-list-item>
        </v-row>

        <v-row class="ml-16">
          <a href="">
            <div class="rectangle">
              <div class="circle"></div>
              <b><p class="button-list-count">5</p></b>
            </div></a
          >
          <a href=""
            ><div class="circle">
              <v-icon color="white" size="20px"
                >mdi-chat-processing-outline</v-icon
              >
            </div></a
          >
        </v-row>
      </v-col>
    </v-row>

    <!-- <MainMobile /> -->
  </v-container>
</template>

<script>
import mainListItems from "../mixins/mainListItems";
// import MainMobile from "./MainMobile";
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
    // MainMobile,
  },
  mixins: [mainListItems],
};
</script>

<style lang="scss">
</style>