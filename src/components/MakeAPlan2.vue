<template>
  <div class="white">
    <v-container fluid class="yellow lighten-5 plan-main-text" fill-height1>
      <v-row>
        <h1 class="">
          The <br />
          Problem
        </h1>
      </v-row>
      <v-row>
        <h2>
          Before we begin, let me give you a brief <br />
          explanation why we need this plan:
        </h2>
      </v-row>
    </v-container>

    <v-container fluid fill-height1>
      <v-row justify="center" class="border1">
        <v-card height="480" width="1280" class="border2 text-center">
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
      </v-row>
    </v-container>

    <v-container fluid>
      <v-form>
        <v-row>
          <v-col cols="12" md="6" lg="6">
            <v-row v-for="i in 4" :key="i">
              <v-text-field :label="`Problem ${i}`" required></v-text-field>
            </v-row>
          </v-col>

          <v-col cols="12" md="2" lg="2"></v-col>
          <v-col cols="12" md="4" lg="4">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </v-col>
        </v-row>
      </v-form>
    </v-container>

    <v-container fluid fill-height1>
      <v-row>
        <h2>Need help? Learn from young mentors</h2>
      </v-row>

      <v-row>
        <v-col cols="12" md="6" lg="6">
          <v-card>
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
          <v-row class="font-weight-bold">
            <v-col cols="10">
              <p>Title of the video</p>
            </v-col>
            <v-col cols="2">
              <p>3:00</p>
            </v-col>
          </v-row>
          <v-row>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </v-row>
        </v-col>
        <v-col cols="12" md="6" lg="6">
          <v-card>
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
          <v-row class="font-weight-bold">
            <v-col cols="10">
              <p>Title of the video</p>
            </v-col>
            <v-col cols="2">
              <p>3:00</p>
            </v-col>
          </v-row>
          <v-row>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </v-row>
        </v-col>
      </v-row>
      <br />
      <v-row>
        <p class="font-weight-bold">Related videos:</p>
        <p class="pink--text">Sample title 1, Sample title 2, Sample title 3</p>
      </v-row>
      <br />
      <br />

      <v-row cols="12" justify="center">
        <v-card width="1000" height="500">
          <v-card-text>
            <v-text-field label="What is the issue that can be solved" required>
              <template v-slot:append>
                <v-icon size="3em" class="pink--text"> mdi-camera </v-icon>
              </template>
            </v-text-field>
          </v-card-text>
          <v-card-actions>
            <v-col cols="12" lg="2">
              <v-btn outlined class="pink white--text">Save</v-btn>
            </v-col>
          </v-card-actions>
        </v-card>
      </v-row>

      <v-row justify="center" align="center" class="pink">
        <h1>
          <span class="yellow--text">What's next? </span>
          <span class="white--text">The Goal</span>
        </h1>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// import Footer from "./Footer";

export default {
  name: "MakeAPlan2",

  components: {
    // Footer,
  },
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>

<style>
</style>