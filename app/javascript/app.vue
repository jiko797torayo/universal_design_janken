<template>
  <div>
    <router-view></router-view>
  </div>
</template>

<script>
import Vue from 'vue'
import VueRouter from 'vue-router'

import JankenRockPage from 'JankenRockPage.vue'
import JankenScissorsPage from 'JankenScissorsPage.vue'
import JankenPaperPage from 'JankenPaperPage.vue'

const router = new VueRouter({
  routes: [
    { path: '/',
      component: JankenRockPage },
    { path: '/janken/rock',
      name: 'JankenRockPage',
      component: JankenRockPage },
    { path: '/janken/scissors',
      name: 'JankenScissorsPage',
      component: JankenScissorsPage },
    { path: '/janken/paper',
      name: 'JankenPaperPage',
      component: JankenPaperPage },
  ]
})

Vue.use(VueRouter)
export default {
  router
}
</script>

<style scoped>
</style>
