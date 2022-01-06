<template>
  <v-app>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Hello! (Introduction)</h1>
      <pre class="text-start">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.
        Ullam laudantium laboriosam quis iusto assumenda
        fugiat distinctio odit enim deserunt impedit.
    </pre
      >
    </div>

    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">(The hook)</h1>
      <pre>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.
        Ullam laudantium laboriosam quis iusto assumenda
        fugiat distinctio odit enim deserunt impedit.
    </pre
      >
    </div>
    <v-main>
      <ShiftProducts />
    </v-main>
  </v-app>
</template>

<script>
import ShiftProducts from "./ShiftProducts.vue";
export default {
  name: "IamNewHere",
  components: {
    ShiftProducts,
  },
  data: () => ({}),
};
</script>
<style lang="scss">

@import "../src/assets/css/style.scss";

</style>
