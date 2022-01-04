<template>
  <v-app>
    <div class="container">
      <div class="pragraph amber lighten-5">
        <h1 class="pink--text font-weight-black text-sm-left">
          I want to know how to help
        </h1>

        <p class="pink--text text-sm-left">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
        </p>
      </div>


 <div class="pragraph">
        <h1 class="black--text font-weight-black text-sm-left">
          Where are you founding?
        </h1>

        <p class="black--text text-sm-left">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
        </p>
      </div>



      <div class=" box blue-grey lighten-5">
          
        <h2 class="pink--text font-weight-black text-sm-center text-header">
          Want to fund young people's ideas? Email us:
        </h2>
        <v-row justify="center">
          <v-col cols="12" sm="6">
            <v-text-field label="Name" single-line></v-text-field>
          </v-col>
        </v-row>
        <v-row justify="center">
          <v-col cols="12" sm="6">
            <v-text-field label="Email" single-line></v-text-field>
          </v-col>
        </v-row>
        <v-row justify="center">
          <v-col cols="12" sm="6">
            <v-text-field label="Message" single-line></v-text-field>
          </v-col>
        </v-row>
        <v-row align="center" justify="space-around">
          <v-btn class="white--text" color="pink"> Submit </v-btn>
        </v-row>
         
      </div>
    </div>
  </v-app>
</template>

<script>
export default {
  name: "Howtohelp",

  data: () => ({}),
};
</script>

<style scoped>
p {
  margin-top: 10px;
  padding: 10px;
  margin-left: 40px;
}
.pragraph{
    margin-top: 100px;
}
.box{
   
    margin-block-start: 50px;
    margin-block-end: 200px;
}

</style>
