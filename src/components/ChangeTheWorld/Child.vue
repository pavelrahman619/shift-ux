<template>
  <v-app>
    <div class="container">
      <v-container class="white">
        <v-row no-gutters>
          <v-col cols="2">
            <div>
              <v-card class="pa-2 amber lighten-1" height="550px" width="100%" outlined>
                <h2 class="white--text font-weight-black text-sm-left"> Plan</h2>
              </v-card>
            </div>
          </v-col>

          <v-col cols="8">
            <v-row no-gutters>
              <v-col cols="12">
                <v-card class="pa-2 amber lighten-3" height="300px" width="100%" outlined>
                  <h2 class="black--text font-weight-black text-sm-left">Make</h2>
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
                <v-row class="round" justify="space-around">
                  <v-avatar v-for="i in 2" :key="i" color="black">
                    {{ i }}
                  </v-avatar>
                </v-row>
              </v-col>

              <v-col cols="12">
                <v-card class="pa-2 pink" height="210px" width="200px">
                  <h2 class="white--text font-weight-black text-sm-left">MakePlan</h2>
                </v-card>
              </v-col>
            </v-row>
          </v-col>
        </v-row>

        <v-row>
          <v-col cols="6">
            <v-card class="pa-2 pink" height="200px" width="100%">
              <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2>
            </v-card>
          </v-col>

          <v-col cols="6">
            <div style="position: relative">
              <v-card class="pa-2 pink" height="450px" width="100%" style="position: absolute ; top: -260px">
                <h2 class="white--text font-weight-black text-sm-left">Make A Plan2</h2>
              </v-card>
            </div>
          </v-col>
        </v-row>




  <v-row>
          <v-col cols="10">
            <v-card class="pa-2 pink" height="200px" width="100%">
              <h2 class="white--text font-weight-black text-sm-left">Make A Plan3</h2>
            </v-card>
          </v-col>

          <v-col cols="2">
            <div style="position: relative">
              <v-card class="pa-2 light-blue darken-4" height="450px" width="100%" style="position: absolute">
                <h2 class="white--text font-weight-black text-sm-left">Make A Plan4</h2>
              </v-card>
            </div>
          </v-col>
        </v-row>


 <v-row>
          <v-col cols="4">
            <v-row no-gutters>
              
                <v-row class="round" justify="space-around">
                  <v-avatar color="black" size="200">
                    
                  </v-avatar>
                </v-row>
            </v-row>

             
          </v-col>

          <v-col cols="8">
            <div style="position: relative">
              <v-card class="pa-2 light-blue darken-5" height="450px" width="100%" style="position: absolute">
                <h2 class="white--text font-weight-black text-sm-left">Make A Plan6</h2>
              </v-card>
            </div>
          </v-col>
        </v-row>



      </v-container>
    </div>
  </v-app>
</template>

<script>
export default {
  name: "Child",

  data: () => ({}),
};
</script>
