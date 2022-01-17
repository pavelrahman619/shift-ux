<template>
  <base-layout>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Shift (products)</h1>
      
        <v-row>
          <v-col lg="6" cols="12">
            <v-row>
              <v-col cols="12" lg="12">
                <v-card class="pa-2 pink box1" height="200px" width="100%" label>
                  <h2 class="white--text font-weight-black text-sm-left">
                    Apply for founding
                  </h2>
                </v-card>
              </v-col>

              <v-col cols="12" lg="12">
                <v-card class="pa-2 pink box1" height="350px" width="100%" label>
                  <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2>
                </v-card>
              </v-col>
            </v-row>
          </v-col>
          <v-col cols="12" lg="6" class="mt-7">
            <v-row>
              <v-col cols="12" lg="12">
                <v-row class="round" justify="space-around">
                  <v-avatar v-for="i in 5" :key="i" color="black">
                    {{ i }}
                  </v-avatar>
                </v-row>

                <v-col cols="12" lg="12">
                  <v-card class="pa-2 pink box1" label>
                    <h2 class="white--text font-weight-black text-sm-left">
                      Learn from a guide
                    </h2>
                  </v-card>
                </v-col>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      
    </div>
  </base-layout>
</template>

<script>
import BaseLayout from "../../App.vue";
export default {
  name: "ShiftProducts",
  components: {
    BaseLayout,
  },

  data: () => ({}),
};
</script>
