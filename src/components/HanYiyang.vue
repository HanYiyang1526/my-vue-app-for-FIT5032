<template>
  <div>
    <h1>MyName</h1>
    <p>{{ name }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Han Yiyang' //
    }
  }
}
</script>

<style scoped>
h1 {
  color: #42b983;
}
</style>
