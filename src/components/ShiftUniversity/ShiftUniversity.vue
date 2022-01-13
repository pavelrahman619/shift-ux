<template>

  <base-layout>
  
    <div class="container">
      <!-- <v-flex xs12 sm12 md4> -->
      <v-card
        class="pa-md-4 mx-lg-auto"
        color="white"
        width="100%"
        height="500px"
        style="box-shadow: none"
      >
        <h1 class="pink--text font-weight-black text-sm-left" cols="12" md="4">
          <br />
          The Guide
        </h1>
        <v-col cols="12" lg="6" md="6">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
            incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
            nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
          </p>
        </v-col>
      </v-card>

      <!-- From -->

      <v-row cols="12" md="6" lg="6">
        <v-card>
          <v-card-title class="font-weight-bold"> From our Mentors </v-card-title>

             <v-toolbar flat class="mainHeader">
      <v-toolbar-title>Sort by:</v-toolbar-title>
      
      <v-toolbar-items class="hidden-xs-only">
      <v-toolbar-items text class="CLICK-ME" @click="$event.target.classList.toggle('pink')">Country</v-toolbar-items>
        <v-btn text class="CLICK-ME" @click="$event.target.classList.toggle('pink')"><router-link to="/">Need more funding</router-link></v-btn>
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
              <v-list-item-title><router-link to="/">Country</router-link></v-list-item-title>
            </v-list-item>
            <v-list-item>
              <v-list-item-title><router-link to="/">Need more funding</router-link></v-list-item-title>
            </v-list-item>
            <v-list-item>
              <v-list-item-title><router-link to="/">Fully-funded</router-link></v-list-item-title>
            </v-list-item>
             <v-list-item>
              <v-list-item-title><router-link to="/">Topic</router-link></v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu>
      </div>
    </v-toolbar>
          

<!-- card -->

 <v-sheet class="mx-auto" elevation="8" max-width="100%">
        <v-slide-group
          v-model="model"
          class="pa-4"
          prev-icon="mdi-chevron-left"
          next-icon="mdi-chevron-right"
          show-arrows
        >
          <v-slide-item v-for="n in 9" :key="n">
            <v-card
              :color="active ? 'primary' : '#FDFBEF'"
              class="ma-4 profile d-flex align-end mb-6"
              height="350"
              width="350"
              @click="toggle"
            >
              <!-- <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2> -->
             
            
              <v-row justify="center">
              <v-btn outlined class=" pink white--text" elevation="2" small
                >Learn more</v-btn></v-row>
              
            </v-card>
          </v-slide-item>
        </v-slide-group>
      </v-sheet>

        </v-card>
      </v-row>

      <!-- From end -->







      <v-row cols="12" md="6" lg="6">
        <v-card>
          <v-card-title class="font-weight-bold"> From our Mentors </v-card-title>
       <v-sheet class="mx-auto" elevation="8" max-width="100%">
        <v-slide-group
          v-model="model"
          class="pa-4"
          prev-icon="mdi-chevron-left"
          next-icon="mdi-chevron-right"
          show-arrows
        >
          <v-slide-item v-for="n in 9" :key="n">
            <v-card
              :color="active ? 'primary' : '#FDFBEF'"
              class="ma-4 profile d-flex align-end mb-6"
              height="350px"
              width="200px"
              @click="toggle"
            >
              <!-- <h2 class="white--text font-weight-black text-sm-left">Make A Plan</h2> -->
             
            
              <v-row justify="center">
              <v-btn outlined class="pink white--text btn-style" elevation="2" small
                >Learn more</v-btn></v-row>
              
            </v-card>
          </v-slide-item>
        </v-slide-group>
      </v-sheet></v-card></v-row>

      

      <!-- Message box -->
      <v-container>
      <v-row cols="12" justify="center">
        <v-card width="500" height="500">
          <v-card-title> Want to inspire young people? Drop us an email </v-card-title>
          <v-card-text>
            <v-text-field label="Name" required> </v-text-field>
            <v-text-field label="Email" required> </v-text-field>
            <v-text-field label="Message" required> </v-text-field>
          </v-card-text>
          <v-card-actions>
            
            <v-row justify="center">
            <v-col cols="12" lg="2">
              <v-btn outlined class="pink white--text btn-style">Submit</v-btn>
            </v-col></v-row>
          </v-card-actions>
        </v-card>
      </v-row>
      </v-container>
      <!-- Message box End -->
      <v-main> </v-main>
    </div>
  </base-layout>
</template>

<script>
import BaseLayout from "../../App.vue";

export default {
  name: "Changeworld",
  components: {
    BaseLayout,
  },

  data: () => ({ 
    }),

    
 
};
</script>
