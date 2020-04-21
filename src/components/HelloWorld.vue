<template>
  <div id="hello-world">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  export default {
    props: ['msg'],
    name: 'HelloWorld',
  }
</script>

<style scoped lang="scss">
  $primary-color: white;
  $bg: red;
  h1 {
    color: $primary-color;
    background-color: $bg;
  }
</style>
