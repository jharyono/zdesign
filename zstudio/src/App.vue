<template>
  <div id="app">
    <Navbar />
  </div>
  <router-view />
</template>

<script>
import Navbar from "@/components/Navbar.vue"

export default {
  components: {
    Navbar
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
body {
  font-family: sans-serif;
  font-size: 16px;
}

a {
  color: black;
  text-decoration: none;
}
</style>
