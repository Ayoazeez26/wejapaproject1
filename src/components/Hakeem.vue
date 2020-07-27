<template>
  <h1>{{ name }}</h1>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name: String
  }
}
</script>

<style scoped>
  h1 {
    margin: 0 auto;
    font-size: 60px;
  }
</style>