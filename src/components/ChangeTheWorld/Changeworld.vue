<template>
  <base-layout>
    <!-- <v-flex xs12 sm12 md4> -->
    <v-card
      class="pa-md-4 mx-lg-auto"
      color="amber lighten-5"
      width="100%"
      height="500px"
      style="box-shadow: none"
    >
      <h1 class="header font-weight-black text-sm-left" cols="12" md="4">
        <br />
        Hello! If you are young <br />
        and have ideas to <br />
        change the world, you <br />
        came to the right place!
      </h1>

      <!-- <v-list-item-title class="text-h5 mb-1">
          Headline 5
        </v-list-item-title> -->
    </v-card>

    <!-- </v-flex> -->
    <v-row>
      <v-col lg="12">
        <v-card>
          <a>
            <img
              height="500px"
              width="100%"
              class="mr-3 image1"
              :src="require('@/assets/cover.png')"
          /></a> </v-card></v-col
    ></v-row>

    <Child />
    <!-- Add video -->

  
      <v-container fluid fill-height1>
        <v-row>
          <v-col cols="12" md="12" lg="8">
            <v-card
              height="480"
              width="1200"
              class="text-center pa-md-4 mx-lg-auto"
              style="box-shadow: none"
            >
              <iframe
                width="100%"
                height="100%"
                src="https://www.youtube.com/embed/nhBVL41-_Cw"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </v-card>
          </v-col>

          <v-col cols="12" md="8" lg="4">
            <h1>
              Meet our first <br />
              Shift groups <br />
              in Myanmar
            </h1>
          </v-col>
        </v-row>
      </v-container>
   
    <v-row justify="center" class="p1">
      <v-col cols="12" md="4">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
          incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
          nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
      </v-col>
    </v-row>

    <!-- end video -->
    <!-- Add Card -->
    <div class="container">
      <h1 class="header font-weight-black text-sm-left" cols="12" md="4">
        Meet the team
      </h1>
      <v-sheet class="mx-auto" elevation="8" max-width="100%">
        <v-slide-group
          v-model="model"
          class="pa-4"
          prev-icon="mdi-chevron-left"
          next-icon="mdi-chevron-right"
          show-arrows
        >
          <v-slide-item v-for="n in 6" :key="n" v-slot="{ active, toggle }">
            <v-card
              :color="active ? 'primary' : '#FDFBEF'"
              class="ma-4 profile"
              height="350"
              width="100%"
              @click="toggle"
            >
            
              <a href="#">
                <img
                  class="mr-3 image1"
                  :src="require('@/assets/card1.png')"
                  height="170px"
                  width="100%"
              /></a>
              <v-card-title> Andy </v-card-title>
              <v-card-text> I am the brain childof shift </v-card-text>
              <div>
                <v-icon size="1em" class="black--text"
                  >mdi-map-marker-star-outline </v-icon
                >Australia
              </div>
              <v-btn outlined class="black--text btn-hobby" elevation="2" x-small
                >Coffee</v-btn
              >
              <v-btn outlined class="black--text btn-hobby" elevation="2" x-small
                >Music</v-btn
              >
              <v-btn outlined class="black--text btn-hobby" elevation="2" x-small
                >Nature</v-btn
              >
            </v-card>
          </v-slide-item>
        </v-slide-group>
      </v-sheet>
    </div>

    <v-main>
      <ShiftProducts />
    </v-main>
  </base-layout>
</template>

<script>
import BaseLayout from "../../App.vue";
import ShiftProducts from "../../components/NewHere/ShiftProducts.vue";
import Child from "./Child.vue";
export default {
  name: "Changeworld",
  components: {
    BaseLayout,
    Child,
    ShiftProducts,
  },

  data: () => ({}),
};
</script>
