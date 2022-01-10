<template>
  <v-app>
    
    <!-- <v-flex xs12 sm12 md4> -->
    <v-card
      class="pa-md-4 mx-lg-auto"
      color="amber lighten-5"
      width="100%"
      height="500px"
      style="box-shadow: none"
    >
      <h1 class="header font-weight-black text-sm-left" cols="8" md="4">
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

    <v-layout justify-center>
      <v-img class="mr-3" src="@/assets/cover.png" height="700px"> </v-img>
    </v-layout>

    <!-- Add video -->



    <v-container fluid fill-height1>
      <v-row justify="center">
        <v-col cols="8">
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

        <v-col cols="4" md="4">
          
          <v-card height="480" width="1200" class="border2 text-center">
            <v-card-title class="font-weight-black">
              
              Meet our first <br />
              Shift groups <br />
              in Myanmar
            </v-card-title>
          </v-card>
          
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

  <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Meet the team</h1>
   
  
  
    </div>





    <v-main>
      <ShiftProducts />
    </v-main>
  </v-app>
</template>

<script>
import ShiftProducts from "../../components/NewHere/ShiftProducts.vue";
export default {
  name: "Changeworld",
    components: {
      ShiftProducts,
    },

  data: () => ({}),
};
</script>
