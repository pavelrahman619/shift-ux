<template>
  <v-app>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Shift (products)</h1>
      <v-container class="white">
<<<<<<< HEAD
        <v-row no-gutters>
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="200px" width="500px" label>
              <h2 class="white--text font-weight-black text-sm-left">
                Apply for founding
              </h2>
=======
        <v-row>
          <v-col cols="6" class="d-flex justify-center">
            <v-card class="pa-2 pink box1 justify-center" height="200px" width="550px" label>
                 <h2 class="white--text font-weight-black text-sm-left"> Apply for founding</h2>
             
>>>>>>> 1e08d9333c6e35ed20dd66287b7f03be9c8992b4
            </v-card>
          </v-col>
          <v-col cols="6" class="mt-7">
            <v-row justify="space-around">
              <v-avatar v-for="i in 5" :key="i" color="black">
                {{ i }}
              </v-avatar>
            </v-row>
          </v-col>
<<<<<<< HEAD
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="350px" width="500px" label>
              <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2>
            </v-card>
          </v-col>
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="350px" width="500px" label>
              <h2 class="white--text font-weight-black text-sm-left">
                Learn from a guide
              </h2>
=======
          <v-col cols="6" class="d-flex justify-center">
            <v-card class="pa-2 pink box1" height="350px" width="550px" label
              > <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2>
            </v-card>
          </v-col>
          <v-col cols="6" class="d-flex justify-center" fill-height>
            <v-card class="pa-2 pink box1" height="350px" width="550px" label>
                  <h2 class="white--text font-weight-black text-sm-left"> Learn from a guide</h2>
             
>>>>>>> 1e08d9333c6e35ed20dd66287b7f03be9c8992b4
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </v-app>
</template>

<script>
export default {
  name: "ShiftProducts",

  data: () => ({


  }),
};
</script>
<style lang="scss">


@import "../src/assets/css/style.scss";


</style>