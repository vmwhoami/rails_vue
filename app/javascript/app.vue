<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
body {
  font-size: 2em;
  text-align: center;
  background-color: aliceblue;
}
</style>
