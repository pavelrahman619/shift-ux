<template>
<base-layout>
    <div>
      <v-card
        class="pa-md-4 mx-lg-auto"
        color="amber lighten-5"
        width="100%"
        height="500px"
        style="box-shadow: none"
      >
        <h1 class="header font-weight-black text-sm-left" cols="12" md="4">
          I want to know how to help
        </h1>

        <v-col cols="12" md="4" lg="6">
          <p class="black--text text-sm-left">
            <br />
            <br />
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
            laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ullam laudantium
            laboriosam quis iusto assumenda fugiat distinctio odit enim deserunt impedit.
          </p></v-col
        >
      </v-card>

      <!-- section-2 -->

      <!-- <v-container fluid> -->

      <div class="container">
        <v-container>
          <h1 class="black--text font-weight-black" cols="12" md="4">
            On going projects
          </h1>
          <v-toolbar flat class="mainHeader">
            <v-toolbar-title>Sort by:</v-toolbar-title>

            <v-toolbar-items class="hidden-xs-only">
              <v-btn text><router-link to="/">Country</router-link></v-btn>
              <v-btn text><router-link to="/">Need more funding</router-link></v-btn>
              <v-btn text><router-link to="/">Fully-funded</router-link></v-btn>
              <v-btn text><router-link to="/">Topic</router-link></v-btn>
            </v-toolbar-items>
            <div class="hidden-sm-and-up">
              <v-menu offset-y>
                <template v-slot:activator="{ on }">
                  <v-app-bar-nav-icon v-on="on"></v-app-bar-nav-icon>
                </template>
                <v-list class="responsiveMenu">
                  <v-list-item>
                    <v-list-item-title
                      ><router-link to="/">Country</router-link></v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title
                      ><router-link to="/"
                        >Need more funding</router-link
                      ></v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title
                      ><router-link to="/">Fully-funded</router-link></v-list-item-title
                    >
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title
                      ><router-link to="/">Topic</router-link></v-list-item-title
                    >
                  </v-list-item>
                </v-list>
              </v-menu>
            </div>
          </v-toolbar>

          <v-sheet class="mx-auto" elevation="8" max-width="100%">
            <v-slide-group
              v-model="model"
              class="pa-4"
              prev-icon="mdi-chevron-left"
              next-icon="mdi-chevron-right"
              show-arrows
            >
              <v-slide-item v-for="n in 6" :key="n" v-slot="{ active, toggle }">
                <v-card
                  :color="active ? 'primary' : '#FDFBEF'"
                  class="ma-4 profile d-flex align-end"
                  height="350"
                  width="250px"
                  @click="toggle"
                >
                 
                
                  <v-row align="end" justify="space-around">
                     
                    <v-btn outlined class="pink white--text"> Found us ! </v-btn>
                  </v-row>
                </v-card>
              </v-slide-item>
            </v-slide-group>
          </v-sheet>
        </v-container>
      </div>

      <!-- end 2 -->

      <div class="container">
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
        <h1 class="black--text font-weight-black text-sm-left" style="margin: 50px">
          I want to know how to help
        </h1>
        <v-layout justify-center>
          <v-img class="mr-3" src="@/assets/l2.png" height="180px" width="70px"> </v-img>
        </v-layout>
        <p style="margin: 50px" class="text-justify">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod veniam aut
          <br />
          magnam molestias quam mollitia eum unde necessitatibus consequatur. Earum
          eum,<br />
          quis amet a deleniti officiis possimus ducimus. Error cupiditate officia<br />
          debitis rem dicta enim animi. Iusto, nesciunt rem? Qui?
        </p>
      </v-container>

      <!-- section-4 -->
      <div class="container">
        <v-card
          class="pa-md-4 mx-lg-auto"
          color="blue-grey lighten-5"
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

          <v-card-actions>
            <v-row align="center" justify="space-around" outlined>
              <v-btn outlined class="pink white--text"> Submit </v-btn>
            </v-row>
          </v-card-actions>
        </v-card>
      </div>
    </div>
  </base-layout>
</template>


<script>
import BaseLayout from "../../App.vue";
export default {
  name: "Howtohelp",
  components: {
    BaseLayout,
  },

  data: () => ({}),
};
</script>

