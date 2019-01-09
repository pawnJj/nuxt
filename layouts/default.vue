<template>
  <div class="main">
    <div>
      <pc-head/>
    </div>
    <nuxt/>
  </div>
</template>
<script>
import pcHead from '~/components/head/pc'
export default {
    components: { pcHead },
    name:''
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #1a1a1a;
}
</style>
