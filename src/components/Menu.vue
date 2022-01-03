<template>
  <v-app>
    <v-card class="flex" flat tile>
      <v-row class="text-center">
        <v-flex align-self-center>
        <v-img
          :src="require('../assets/l1.png')"
          class="my-3 white"
          contain
          height="100" 
        />

        <v-container class="white lighten-5">
          <v-row no-gutters>
            <v-col cols="12" sm="6" md="6">
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="pink--text font-weight-black"
                    >I am new here<v-chip class="ma-2 font-weight-light" color="pink lighten-1" text-color="white">
                      You are here
                    </v-chip></v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class="black--text font-weight-black"
                    >I want to change the world</v-list-item-title
                  >
                  <v-list>I want to make a plan</v-list>
                  <v-list>I want to make a plan</v-list>
                  <v-list>I want to make a plan</v-list>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <a href="#"
                    ><v-list-item-title class="black--text font-weight-black"
                      >I want to found their ideas</v-list-item-title
                    ></a
                  >
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col cols="6" md="6">
              <v-list-item>
                <v-list-item-content>
                  <a href="#"
                    ><v-list-item-title class="black--text font-weight-black"
                      >Want to talk?</v-list-item-title
                    ></a
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <a href="#"
                    ><v-list-item-title class="black--text font-weight-black"
                      >My plan</v-list-item-title
                    ></a
                  >
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-container>
        <v-card-text>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4 black--text" icon>
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>
        </v-flex>


        <!-- <v-divider></v-divider> -->
      </v-row>
    </v-card>
  </v-app>

</template>

<script>
export default {
  name: "Menu",

  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>
