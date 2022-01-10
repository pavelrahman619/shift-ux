<template>
  <div>
    
    <v-navigation-drawer
      app
      right
      hide-overlay="true"
      v-model="drawer"
      width="100%"
      elevation="0"
   
    >
      <!--  -->
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
   
    </v-navigation-drawer>

    <v-app-bar app color="amber lighten-5" elevation="0">
      <a href="#">
        <img
          class="mr-3"
          :src="require('../assets/l1.png')"
          height="40"
           
      /></a>
<v-spacer></v-spacer>
      <v-app-bar-nav-icon @click="drawer = !drawer" elevation="0"></v-app-bar-nav-icon> 
    </v-app-bar>
  </div>
</template>

<script>

export default {
    name: "Header",
    components: {
    // Menu,
  },
  data: () => ({ drawer: false }),
};
</script>

