<template>
  <v-container fluid fill-height1 class="yellow lighten-5">
    <v-card class="border2" height="100%">
      <v-text-field v-for="i in 4" :key="i" :label="`Problem ${i}`" required></v-text-field>
    </v-card>
    <div class="makeaplan-hover-shape-mobile"><p>I need help</p></div>

  </v-container>
</template>

<script>
export default {};
</script>

<style>
</style>