<template>
  <v-container fluid fill-height1 class="yellow lighten-5">
    <v-navigation-drawer
      right
      hide-overlay="true"
      v-model="helpDrawer"
      width="100%"
      height="100%"
      absolute
    >
      <MakeAPlanHoverMenu></MakeAPlanHoverMenu>
    </v-navigation-drawer>

    <v-card class="border2" height="100%">
      <v-text-field
        v-for="i in 4"
        :key="i"
        :label="`Problem ${i}`"
        required
      ></v-text-field>
    </v-card>
    <div @click="helpDrawer = !helpDrawer" class="makeaplan-hover-shape-mobile">
      <p>I need help</p>
    </div>
  </v-container>
</template>

<script>
import MakeAPlanHoverMenu from "@/components/MakeAPlan/MakeAPlanHoverMenu";

export default {
  components: {
    MakeAPlanHoverMenu,
  },

  data: () => ({ helpDrawer: false }),
};
</script>

<style>
</style>