<template>
  <div class="introduce">
    <h1>{{ name }}</h1>
    </div>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color:rgb(235, 26, 123);
  font-size: 45px;
}
</style>