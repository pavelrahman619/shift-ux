<template>
  <v-container yellow fluid fill-height1>
    <v-row>
      <v-row class="main-head-text" align="center" justify="center">
        <h1>
          <b>Let's change the world one campaign at a time</b>
        </h1>
      </v-row>


    </v-row>
  </v-container>
</template>

<script>
import mainListItems from '../mixins/mainListItems';
export default {
  name: "Main",
  // data: function () {
  //   return {
  //     items: [
  //       "I am new here",
  //       "I want to change the world",
  //       "I want to know how to help",
  //     ],
  //   };
  // },
  mixins: [mainListItems]
};
</script>

<style lang="scss">
// .container {
//   padding: 5em 0 5em 0;
// }
</style>

