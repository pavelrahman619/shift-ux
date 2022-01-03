<template>
  <v-container>
    <div class="container">
      <div>
        <h1><b>Let's change the world one campaign at a time</b></h1>
      </div>

      <div class="main-list">
        <v-list-item>
          <v-list-item-content>
            <a href="#"
              ><v-list-item-title class="pink--text"
                >I am new here</v-list-item-title
              ></a
            >
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <a href="#"
              ><v-list-item-title class="pink--text"
                >I want to change the world</v-list-item-title
              ></a
            >
          </v-list-item-content>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <a href="#"
              ><v-list-item-title class="pink--text"
                >I want to know how to help</v-list-item-title
              ></a
            >
          </v-list-item-content>
        </v-list-item>
      </div>

      <div class="buttons">
        <img :src="require('../assets/images/button1.png')" />
        <img :src="require('../assets/images/button2.png')" />
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style>
</style>