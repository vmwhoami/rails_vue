<template>
  <div>
    <p v-text="message"/>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Some message"
    }
  }
}
</script>

<style scoped>
.triangle-up {
  width: 1500px;
  height: 400px;
  background: red;
}
p {
  font-size: 2em;
  text-align: center;
}
</style>
