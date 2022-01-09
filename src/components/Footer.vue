<template>
  <v-footer app absolute dark padless id="footer">
    <v-card flat tile class="indigo darken-4 white--text text-center flex">
      <v-row class="text-center">
        <v-col lg="12">
          <v-container fluid class="indigo darken-4">
            <v-row no-gutters>
              <v-col cols="12" sm="6" md="6">
                <v-list-item>
                  <v-list-item-content>
                    <v-list-item-title class="pink--text font-weight-black"
                      >{{ items[0]
                      }}<v-chip
                        class="ma-2 font-weight-light"
                        color="pink lighten-1"
                        text-color="white"
                      >
                        You are here
                      </v-chip></v-list-item-title
                    >
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-content>
                    <v-list-item-title class="white--text font-weight-black">{{
                      items[1]
                    }}</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-content>
                    <a href="#"
                      ><v-list-item-title class="white--text">{{
                        items[2]
                      }}</v-list-item-title></a
                    >
                  </v-list-item-content>
                </v-list-item>
              </v-col>

              <v-col cols="6" md="6">
                <v-list-item>
                  <v-list-item-content>
                    <a href="#"
                      ><v-list-item-title class="white--text"
                        >Want to talk?</v-list-item-title
                      ></a
                    >
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-content>
                    <a href="#"
                      ><v-list-item-title class="white--text"
                        >My plan</v-list-item-title
                      ></a
                    >
                  </v-list-item-content>
                </v-list-item>
              </v-col>
            </v-row>
          </v-container>
          <v-card-text>
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-4 dark--text"
              icon
            >
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
import mainListItems from "../mixins/mainListItems";

export default {
  name: "Footer",

  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  mixins: [mainListItems],
};
</script>

<style scoped>
.container {
  height: none;
}
</style>
