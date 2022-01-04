<template>
  <v-app>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Shift (products)</h1>
      <v-container class="white">
        <v-row no-gutters>
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="200px" width="450px" label>
                 <h2 class="white--text font-weight-black text-sm-left"> Apply for founding</h2>
             
            </v-card>
          </v-col>
          <v-col cols="4" class="round">
            <v-row justify="space-around">
              <v-avatar v-for="i in 5" :key="i" color="black">
                {{ i }}
              </v-avatar>
            </v-row>
          </v-col>
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="350px" width="450px" label
              > <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2>
            </v-card>
          </v-col>
          <v-col cols="6">
            <v-card class="pa-2 pink box1" height="350px" width="450px" label>
                  <h2 class="white--text font-weight-black text-sm-left"> Learn from a guide</h2>
             
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

  data: () => ({}),
};
</script>
<style>
h1 {
  margin-top: 20px;
  margin-left: 50px;
}
.size {
  height: 113px;
}
pre {
  margin-top: 30px;
}
.box1 {
  margin: 20px;
  padding: 10px;
  border-style: solid;
  border-width: 10px;
  border-color: rgb(7, 7, 7);
 
}

.round{
    margin: 20px;
  padding: 10px; 


}
</style>
