<template>
  <div class="hello">
    <!-- <h1>{{ msg }}</h1>
    <div>
      <span v-if="autor != null">{{ autor }}</span>
      <span>{{ teste }}</span>
    </div> -->
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    autor: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #42b983;
}
</style>
