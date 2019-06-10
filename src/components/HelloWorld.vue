<template>
  <div class="hello">
    <label for="width">Width</label>
    <input name="width" type="number" v-model="width">
    <input type="number" v-model="height">
  </div>
</template>

<script>
export default {
  data () {
    return {
      width: 4,
      height: 5
    }
  },

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
