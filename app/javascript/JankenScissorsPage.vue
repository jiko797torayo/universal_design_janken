<template>
  <div id="app">
    <router-link :to="{ name: 'JankenPaperPage'}">
      <img src="~images/cyoki.gif" />
    </router-link>
  </div>
</template>

<script>
import "images/cyoki.gif"
export default {
  data: function () {
    return {
      message: "チョキ！"
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
