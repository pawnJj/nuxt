<template>
  <div class="">
    <div>
      <pc-head/>
    </div>
    <template>
      <background/>
      
    </template>
    <div class="main">
      <nuxt/>
    </div>
  </div>
</template>
<script>
import pcHead from '~/components/head/pc'
import Background from '~/components/background'
export default {
    components: { pcHead,Background },
    name:''
}
</script>

<style>
.main{
  position: relative;
}
</style>
