<template>
  <footer class="site-footer">
    {{ $siteConfig.siteName }} &copy; {{ new Date().getFullYear() }} - All
    Rights Reserved
    <br />
    Made with <span style="color: #46b9e6;">&#9829;</span> with Nuxt.js and
    Netlify
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>

<style scoped>
footer {
  background: #141114;
  padding: 20px 10px;
  text-align: center;
  transition: 0.5s ease all;
  color: #46b9e6
}
</style>
