<template>
  <div id="app">
    <router-link :to="{ name: 'JankenRockPage'}">
      <img src="~images/par.gif" />
    </router-link>
  </div>
</template>

<script>
import "images/par.gif"
export default {
  data: function () {
    return {
      message: "パー！"
    }
  }
}
</script>

<style scoped>
img {
  display: block;
  margin: auto;
}
</style>
