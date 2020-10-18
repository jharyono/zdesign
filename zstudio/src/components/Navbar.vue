<template>
  <header class="header">
    <div class="nav left-nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/services">Services</router-link>
    </div>
    <div class="nav logo">
      <router-link to="/">
        <span>Zanara</span>
        <span>Design</span>
      </router-link>
    </div>
    <div class="nav right-nav">
      <router-link to="/gallery">Gallery</router-link>
      <router-link to="/contact">Contact</router-link>
      <router-link to="/location">Location</router-link>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-content: center;
}

.nav {
  display: inline-flex;
  padding: 12px 0;
}

.left-nav a,
.right-nav a {
  padding: 0 16px;
}
</style>
