<template>
  <div>
    <h1>This Is User Component</h1>
    <hr>
    <button @click="navigateToHome">Go To Home</button>
    <hr>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  methods: {
    navigateToHome() {
      this.$router.push({ name: 'home' })
    }
  }
}
</script>

<style >
</style>
