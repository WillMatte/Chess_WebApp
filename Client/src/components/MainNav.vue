<script lang="ts">
import {defineComponent} from "vue";
import {RouterLink} from "vue-router";

export default defineComponent({
  data() {
    return {

    }
  },
  components:{}
})
</script>

<template>
  <nav>
    <ul>
      <li>
        <RouterLink to="/" class="main-link">Home</RouterLink>
      </li>
      <li>
        <RouterLink to="/a" class="main-link">Play</RouterLink>
      </li>
      <li>
        <RouterLink to="/" class="main-link">Profile</RouterLink>
      </li>
      <li>
        <RouterLink to="/" class="main-link">Login</RouterLink>
      </li>
    </ul>
  </nav>
</template>

<style scoped lang="sass">
  nav
    ul
      list-style: none
      margin: 0
      padding: 0
      .main-link
        display: inline-block
        text-decoration: none
        color: white
        text-transform: uppercase
        font-size: 1.3rem
        width: 100%
        padding: 2rem 2rem 2rem 2rem
        &:hover
          background-color: #C4AE78
</style>
