<script lang="ts">
import {RouterView} from 'vue-router'
import MainNav from '@/components/MainNav.vue';

export default {
  components: {MainNav, RouterView},

}
</script>

<template>
  <section class="row container-lg">
    <header class="col-3">
      <main-nav/>
    </header>
    <RouterView class="col-9"/>
  </section>
</template>

<style lang="sass">
body
  color: #F9F6F0
  background-color: #171515
  width: 100%
  header
    height: 100vh
    padding: 0 !important
    background-color: #6F5B3E
</style>
