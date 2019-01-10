<template>
  <section class="container">
    <div>
      <!-- <logo/> -->
      <h1 class="title">
        
      </h1>
      
      <div class="aa"></div>
      <p @click="changeTheme('theme1')">11</p>
      <p @click="changeTheme('theme2')">22</p>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  methods: {
    changeTheme (theme) {
      window.document.documentElement.setAttribute('data-theme', theme)
    }
  }
}
</script>

<style lang="scss">
.aa{
  width: 100px;
  height: 100px;
  @include bg_color($background-color-theme1)
}
.title {
  @include font_color($font-color-theme2)
}
</style>
