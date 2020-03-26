<template>
  <div id="app">
    <router-link :to="{ name: 'JankenScissorsPage'}">
      <p>{{ message }}</p>
    </router-link>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Rock!"
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
