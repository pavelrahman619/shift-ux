<template>
  <div class="white">
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

    <v-container fluid fill-height1>
      <v-row>
        <p class="pr-3">CURRENT PROJECTS</p>
        <p class="pink--text">By Country</p>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// import Footer from "./Footer";

export default {
  name: "MakeAPlan3",

  components: {
    // Footer,
  },
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>

<style lang="scss">
</style>