<template>
  <base-layout>
    <div class="container">
      <v-container class="white">
        <v-row no-gutters>
          <v-col cols="2">
            <div>
              <v-card class="pa-2 box5" color="#0B0B2B" height="550px" width="100%">
                <h2 class="black--text font-weight-black text-sm-left">Plan</h2>
              </v-card>
            </div>
          </v-col>

          <v-col cols="8">
            <v-row no-gutters>
              <v-col cols="12">
                <v-card class="box3" height="300px" width="100%" color="#FFD236">
                  <h1 class="black--text font-weight-black text-sm-left test"><br>We shape
                  <br>changemakers to 
                  <br>lead our future</h1>
                </v-card>

                <v-col cols="4">
                  <v-card>
                    <v-avatar height="250px" width="230px">
                      <img src="https://cdn.vuetifyjs.com/images/john.jpg" alt="John" />
                    </v-avatar>
                  </v-card>
                </v-col>
              </v-col>
            </v-row>
          </v-col>

          <v-col cols="2">
            <v-row no-gutters>
              <v-col cols="12">
                <v-row class="pa-2 round" justify="space-around">
                  <v-avatar v-for="i in 2" :key="i" color="#0B0B2B">
                    {{ i }}
                  </v-avatar>
                </v-row>
              </v-col>

              <v-col cols="8">
                <v-card class="pa-2 box4"> </v-card>
              </v-col>
            </v-row>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="6">
            <v-card class="pa-2 box3" color="#0B0B2B" height="200px" width="100%">
              <h2 class="black--text font-weight-black text-sm-left">Make A Plan</h2>
            </v-card>
          </v-col>

          <v-col cols="6">
            <div style="position: relative">
              <v-card
                class="pa-2 box3"
                height="460px"
                width="100%"
                style="position: absolute; top: -260px; color: #ffd236"
              >
                <h1 class="black--text font-weight-black text-sm-left">
                  <br> We fund
                  <br>campaigns
                  <br>that do
                  <br>good
                </h1>
              </v-card>
            </div>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="10">
            <v-card>
              <a>
                <img
                  height="500px"
                  width="100%"
                  class="mr-3 image1"
                  :src="require('@/assets/cover.png')"
              /></a>
            </v-card>
          </v-col>

          <v-col cols="2">
            <div style="position: relative">
              <v-card class="pa-2" height="500px" width="100%" color="#0B0B2B">
                <h2 class="black--text font-weight-black text-sm-left">Make A Plan4</h2>
              </v-card>
            </div>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="4">
            <v-row no-gutters>
              <v-row class="pa-2 round" justify="space-around">
                <v-avatar color="#0B0B2B" size="230"> </v-avatar>
              </v-row>
            </v-row>
          </v-col>

          <v-col cols="8">
            <div style="position: relative">
              <v-card class="pa-2 box3" color="#FFD236" height="250px" width="100%">
                <h1 class="black--text font-weight-black text-sm-left"> Our tools are simple,
                <br>accessible and
                <br>jargon-free.</h1>
              </v-card>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </base-layout>
</template>

<script>
export default {
  name: "Child",

  data: () => ({}),
};
</script>
