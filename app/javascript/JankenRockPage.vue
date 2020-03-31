<template>
  <div id="app">
    <router-link :to="{ name: 'JankenScissorsPage'}">
      <img src="~images/guu.gif" />
    </router-link>
  </div>
</template>

<script>
import "images/guu.gif"
export default {
  data: function () {
    return {
      message: "グー！"
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
