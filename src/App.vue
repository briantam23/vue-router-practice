<template>
  <div id="app">
    <li class="nav-item">
      <router-link class="nav-link" to="/blog">Blog</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/services">Services</router-link>
    </li>
    <li class="nav-item">
      <router-link class="nav-link" to="/contact">contact</router-link>
    </li>
    <router-view/>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style>

</style>
