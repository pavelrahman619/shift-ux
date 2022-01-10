<template>
  <v-app>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">Hello! (Introduction)</h1>
      <p class="text-start">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.<br/>
        Ullam laudantium laboriosam quis iusto assumenda<br/>
        fugiat distinctio odit enim deserunt impedit.<br/>
    </p
      >
    </div>

    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left">(The hook)</h1>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.<br/>
        Ullam laudantium laboriosam quis iusto assumenda<br/>
        fugiat distinctio odit enim deserunt impedit.<br/>
    </p
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
