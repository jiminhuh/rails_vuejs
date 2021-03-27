<template>
  <div id="app">
    <p>{{ message }}</p>
    <Users />
  </div>
</template>

<script>

import Users from './components/Users.vue'

export default {
  name: "App",
  components: {
    Users
  },
  data: function () {
    return {
      message: "Hello!"
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
