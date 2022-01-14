<template>
 <base-layout>
    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left" cols="12" md="4">Hello! (Introduction)</h1>
      <p class="text-start">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit.<br/>
        Ullam laudantium laboriosam quis iusto assumenda<br/>
        fugiat distinctio odit enim deserunt impedit.<br/>
    </p
      >
    </div>

    <div class="container">
      <h1 class="pink--text font-weight-black text-sm-left" cols="12" md="4">(The hook)</h1>
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
  </base-layout>
</template>

<script>
import BaseLayout from "../../App.vue";
import ShiftProducts from "./ShiftProducts.vue";
export default {
  name: "IamNewHere",
  components: {
    BaseLayout,
    ShiftProducts,
  },
  data: () => ({}),
};
</script>
