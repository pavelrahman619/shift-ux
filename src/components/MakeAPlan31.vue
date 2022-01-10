<template>
  <div class="white">
    <v-container fluid class="yellow lighten-5 plan-main-text" fill-height1>
      <v-row>
        <h1 class="">
          The Audience
        </h1>
      </v-row>
      <v-row>
        <h2>
          Who can change the problem?
        </h2>
      </v-row>
    </v-container>

    <v-container fluid fill-height1>
      <v-row justify="center" class="align-center">
        <v-card>
          <v-col>
            <iframe
              width="100%"
              height="100%"
              src="https://www.youtube.com/embed/nhBVL41-_Cw"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </v-col>
        </v-card>
      </v-row>
    </v-container>

    <v-container fluid>
      <v-form>
        <v-row>
          <v-col cols="6">
            <v-row>
              Add picture here
            </v-row>
          </v-col>

          <v-col cols="2"></v-col>
          <v-col cols="4">
            <v-row>

            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
            </v-row>
            <v-row>

              <span v-for="i in 3" :key="i" class="circle-empty"></span>
            </v-row>

          </v-col>
        </v-row>
      </v-form>
    </v-container>

    <v-container fluid>
      <v-form>
        <v-row>
          <v-col cols="6">
            <v-row v-for="i in 3" :key="i">
              <v-text-field :label="`Goal ${i}`" required></v-text-field>
            </v-row>
          </v-col>

          <v-col cols="2"></v-col>
          <v-col cols="4">
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
        <v-col cols="12" lg="6">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/nhBVL41-_Cw"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
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
        <v-col cols="12" lg="6">
          <iframe
            width="560"
            height="315"
            src="https://www.youtube.com/embed/nhBVL41-_Cw"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
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
        <v-card width="1000" height="500" class="d-flex flex-column">
          <v-spacer></v-spacer>
          <v-card-text>
            <v-text-field label="Who can change the problem?" required>
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
          <span class="white--text">The Audience</span>
        </h1>
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

<style>
</style>