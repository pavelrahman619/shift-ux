<template>
  <v-container class="white" fluid fill-height1>
    <v-container fluid class="yellow lighten-5 plan-main-text" fill-height1>
      <v-row>
        <v-col cols="12" md="6" lg="6">
          <h1 class="">
            The <br />
            Campaigns
          </h1>
        </v-col>

        <v-col cols="12" md="6" lg="6">
          <h2>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </h2>
        </v-col>
      </v-row>
    </v-container>

    <!-- FEATURED PROJECT -->
    <v-container fluid fill-height1 class="indigo darken-4 white--text">
      <v-row>
        <h2>FEATURED PROJECT</h2>
      </v-row>

      <v-row>
        <v-col cols="12" md="8" lg="8">
          <v-img
            class="rounded-xl"
            src="@/assets/images/campaigns/1.png"
            alt="campaigns1"
          ></v-img>
        </v-col>
        <v-col
          class="d-flex align-center justify-center"
          cols="12"
          md="4"
          lg="4"
        >
          <h1>
            "We want <br />
            clean air <br />
            in Myanmar"
          </h1>
        </v-col>
      </v-row>
    </v-container>
<br>

    <!-- CURRENT PROJECTS -->
    <v-container fluid>
      <v-row>
        <p class="pr-3">CURRENT PROJECTS</p>
        <p class="pink--text">By Country</p>
      </v-row>
      <v-row>
        <v-col
          cols="12"
          md="4"
          lg="4"
          v-for="n in 6"
          :key="n"
          class="d-flex justify-center"
        >
          <v-card
            :color="active ? 'primary' : '#FDFBEF'"
            class="d-flex flex-column"
            min-height="480"
            height="360"
            width="360"
          >
            <v-img
              height="100"
              width="auto"
              alt="pic"
              src="@/assets/images/campaigns/2.png"
            ></v-img>
            <v-spacer></v-spacer>
            <v-card-actions>
              <v-row justify="center">
                <v-btn
                  outlined
                  class="pink white--text btn-style rounded"
                  elevation="2"
                  small
                  >Fund Us</v-btn
                >
              </v-row>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <v-row class="justify-center">
        <v-btn
          outlined
          class="pink white--text btn-style rounded"
          elevation="2"
          x-large
          >Load More</v-btn
        >
      </v-row>
    </v-container>

    <!-- PEOPLE BEHIND SHIFT -->
    <v-container fluid fill-height1>
      <v-row>
        <h2>People behind Shift</h2>
      </v-row>
      <v-row>
        <v-col cols="12" md="4" lg="4">
          <v-row class="pl-12"> Core team </v-row>
          <v-row>
            <v-slide-group
              v-model="model"
              class=""
              prev-icon="mdi-chevron-left"
              next-icon="mdi-chevron-right"
              show-arrows
            >
              <v-slide-item v-for="n in 9" :key="n">
                <v-card
                  :color="active ? 'primary' : '#FDFBEF'"
                  class="rounded-xl"
                  height="350"
                  width="350"
                >
                  <v-img
                    src="@/assets/images/campaigns/3.png"
                    alt="campaigns1"
                    height=""
                  ></v-img>
                </v-card>
              </v-slide-item>
            </v-slide-group>
          </v-row>
        </v-col>

        <v-col cols="12" md="8" lg="8">
          <v-row class="pl-12"> The Fun Adults </v-row>
          <v-row>
            <v-slide-group
              v-model="model"
              class=""
              prev-icon="mdi-chevron-left"
              next-icon="mdi-chevron-right"
              show-arrows
            >
              <v-slide-item v-for="n in 9" :key="n">
                <v-card
                  :color="active ? 'primary' : '#FDFBEF'"
                  class="rounded-xl"
                  height="350"
                  width="350"
                >
                  <v-img
                    src="@/assets/images/campaigns/3.png"
                    alt="campaigns1"
                    height=""
                  ></v-img>
                </v-card>
              </v-slide-item>
            </v-slide-group>
          </v-row>
        </v-col>
      </v-row>
      <br />

      <v-row>
        <v-col cols="12" md="7" lg="7">
          <v-row class="pl-12"> Partners </v-row>
          <v-row>
            <v-slide-group
              v-model="model"
              class=""
              prev-icon="mdi-chevron-left"
              next-icon="mdi-chevron-right"
              show-arrows
            >
              <v-slide-item v-for="n in 9" :key="n">
                <v-card
                  :color="active ? 'primary' : '#FDFBEF'"
                  class="rounded-xl"
                  height="350"
                  width="350"
                >
                  <v-img
                    src="@/assets/images/campaigns/3.png"
                    alt="campaigns1"
                    height=""
                  ></v-img>
                </v-card>
              </v-slide-item>
            </v-slide-group>
          </v-row>
        </v-col>

        <v-col cols="12" md="5" lg="5">
          <v-row class="pl-12"> Young creators </v-row>
          <v-row>
            <v-slide-group
              v-model="model"
              class=""
              prev-icon="mdi-chevron-left"
              next-icon="mdi-chevron-right"
              show-arrows
            >
              <v-slide-item v-for="n in 9" :key="n">
                <v-card
                  :color="active ? 'primary' : '#FDFBEF'"
                  class="rounded-xl"
                  height="350"
                  width="350"
                >
                  <v-img
                    src="@/assets/images/campaigns/3.png"
                    alt="campaigns1"
                    height=""
                  ></v-img>
                </v-card>
              </v-slide-item>
            </v-slide-group>
          </v-row>
        </v-col>
      </v-row>
    </v-container>


    <!-- EMAIL US -->
    <v-container fluid>
        <v-card
          class="pa-md-4 mx-lg-auto"
          color="blue-grey lighten-5"
          style="box-shadow: none"
        >
          <h2 class="black--text font-weight-black text-sm-center text-header">
            Want to fund young people's ideas? Email us:
          </h2>
          <v-row justify="center">
            <v-col cols="12" md="6" lg="6">
              <v-text-field label="Name" single-line></v-text-field>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="12" md="6" lg="6">
              <v-text-field label="Email" single-line></v-text-field>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="12" md="6" lg="6">
              <v-text-field label="Message" single-line></v-text-field>
            </v-col>
          </v-row>

          <v-card-actions>
            <v-row align="center" justify="space-around" outlined>
              <v-btn outlined class="pink white--text"> Submit </v-btn>
            </v-row>
          </v-card-actions>
        </v-card>
      </v-container>

      
  </v-container>
</template>

<script>
export default {
  name: "Campaigns",

  components: {},
  data: () => ({}),
};
</script>

<style lang="scss">
</style>