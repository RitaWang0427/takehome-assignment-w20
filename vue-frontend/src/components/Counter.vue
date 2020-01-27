<template>
  <div id = "change">
     <b-button v-on:click="count += 1">Add 1</b-button>
     <b-button v-if="count > 0" v-on:click="count -= 1">Subtract 1</b-button>
     <p>counter = {{count}}. </p>
  </div>
</template>
<script>
export default {
  e1 : "change",
  data() {
    return{
      count: 0
    };
  },
  props :{
    count: Number
  },
};
</script>

<style>
</style>


