<template>
  <div class="masthead clearfix">
    <div class="inner">
      <h3 class="masthead-brand"><router-link class="logo" to="/">Diogenes.dog</router-link></h3>
      <nav class="nav nav-masthead">
        <router-link class="nav-link" to="/">Home</router-link>
        <router-link class="nav-link" to="/about">About</router-link>
        <router-link class="nav-link" to="/skills">Skills</router-link>
        <a class="nav-link" target="_blank" href="https://github.com/devyhj">Github</a>
        <a class="nav-link" target="_blank" href="https://www.linkedin.com/in/hojuneyoo/">LinkedIn</a>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style>
.logo:hover {
	text-decoration: none;
}
</style>