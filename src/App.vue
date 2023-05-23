<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<template>
  <!-- Header -->
  <AppHeader />
  <!-- /Header -->
  <!-- main -->
  <router-view></router-view>
  <!-- /main -->
</template>

<style lang="scss"></style>