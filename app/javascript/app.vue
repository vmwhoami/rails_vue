<template>
  <div>
    <p v-text="message"/>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Ea v shoke?"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
