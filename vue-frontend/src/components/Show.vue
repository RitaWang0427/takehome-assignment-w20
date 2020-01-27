<template>
  <!-- PART 4: Add your code here -->
  <div>
    <p>{{name}}.</p>
    <Counter :count = "episodes_seen"/>
  </div>
</template>

<script>
// PART 4: Add your code here
import Counter from "./Counter.vue";
export default {
  components: {
    Counter
  },
  props: {
    id: Number,
    name: String,
    episodes_seen: Number
  }
};
</script>

<style>
</style>
