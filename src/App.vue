<template>
  <Nav />
  <router-view/>
</template>

<script lang="ts">
import Nav from "@/components/Navbar/Navbar.vue"

export default {
  components: {
    Nav
  }
}
</script>

<style lang="scss">
</style>