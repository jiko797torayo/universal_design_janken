<template>
  <div id="app">
    <router-link :to="{ name: 'JankenRockPage'}">
      <p>{{ message }}</p>
    </router-link>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Paper!"
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
