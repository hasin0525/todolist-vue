<template>
  <div class="root">
    <p>{{originalPrice}}</p>
    <p>{{doublePrice}}</p>
    <p>{{triplePrice}}</p>
  </div>
</template>

<script>
import { mapGettes } from "vuex";

export default {
  computed: {
    ...mapGettes(["originalPrice", "doublePrice", "triplePrice"])
  }
};
</script>

<style>
</style>