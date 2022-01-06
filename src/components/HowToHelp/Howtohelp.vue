<template>
  <v-app>
    <div class="container white">
      <v-card
        class="pa-md-4 mx-lg-auto"
        color="amber lighten-5"
        width="100%"
        height="500px"
        style="box-shadow: none"
      >
        <h1 class="pink--text font-weight-black text-sm-left">
          I want to know how to help
        </h1>
        <p class="pink--text text-sm-left" text-align="justify">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          <br />
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.<br />
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium<br />
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
        </p>
      </v-card>

      <!-- section-2 -->

      <v-container fluid>
        
 <div class="container">
      <h1 class="black--text font-weight-black text-sm-left">On going projects</h1>
      <pre>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.
        Ullam laudantium laboriosam quis iusto assumenda
        fugiat distinctio odit enim deserunt impedit.
    </pre
      >
    </div>
        <v-row no-gutters>
      
          <v-col cols="6">
            <v-card
              class="pa-2 amber lighten-5 mx-auto"
              height="350px"
              width="400px"
              outlined
            >
              <v-row align="center" justify="space-around">
                <v-btn class="white--text" color="pink">Found us ! </v-btn>
              </v-row>
            </v-card>
          </v-col>
          <v-col cols="6">
            <v-card
              class="pa-2 amber lighten-5 mx-auto"
              height="350px"
              width="400px"
              outlined
            >
              <v-row align="end" justify="space-around">
                <v-btn class="white--text" color="pink"> Found us ! </v-btn>
              </v-row>
            </v-card>
          </v-col>
        </v-row>
      </v-container>

      <!-- end 2 -->

      <div class="white">
        <h1 class="black--text font-weight-black text-sm-left" style="margin: 50px">
          Where are you founding?
        </h1>

        <p class="black--text text-sm-left">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
          <br />
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.<br />
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium<br />
          laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
        </p>
      </div>

      <!-- section-3 -->
      <v-container>
        <div class="white">
          <h1 class="black--text font-weight-black text-sm-left" style="margin: 50px">
            I want to know how to help
          </h1>
          <v-layout justify-center>
            <v-img class="mr-3" src="@/assets/l2.png" height="180px" width="70px">
            </v-img>
          </v-layout>
          <p style="margin: 50px" class="text-justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod veniam aut
            <br />
            magnam molestias quam mollitia eum unde necessitatibus consequatur. Earum
            eum,<br />
            quis amet a deleniti officiis possimus ducimus. Error cupiditate officia<br />
            debitis rem dicta enim animi. Iusto, nesciunt rem? Qui?
          </p>
        </div>
      </v-container>

      <!-- section-4 -->
      <div class="box blue-grey lighten-5">
        <v-card
          class="box pa-md-4 mx-lg-auto"
          color="blue-grey lighten-5"
          width="100%"
          height="500px"
          style="box-shadow: none"
        >
          <h2 class="black--text font-weight-black text-sm-center text-header">
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
        </v-card>
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
  padding: 3px;
  margin-left: 40px;
}
.box {
  margin-block-start: 50px;
  margin-block-end: 200px;
}
</style>
