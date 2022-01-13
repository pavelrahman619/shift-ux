<template>
  <v-container class="pink white--text" fluid fill-height1>
    <v-row class="ma-5">
      <v-col cols="12" lg="6">
        <v-row justify="center">
          <iframe
            width="100%"
            height="100%"
            src="https://www.youtube.com/embed/nhBVL41-_Cw"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </v-row>
        <v-row class="font-weight-bold">
          <p>Title of the video</p>
        </v-row>
        <v-row>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat.
          </p>
        </v-row>
      </v-col>
    </v-row>
    <v-row>
      <v-btn rounded outlined class="white--text">
        <v-icon class="white--text">mdi-refresh</v-icon>
        Show me more</v-btn
      >
      <a href="#">Go to guide page</a>
      <v-btn class="pink white--text">Go to Guide Page</v-btn>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "MakeAPlanHoverMenu",

  data: () => ({}),
};
</script>
