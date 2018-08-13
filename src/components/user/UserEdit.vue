<template>
  <div>
    <h1>Component User Edit</h1>
    <p>Locale: {{ $route.query.locale }}</p>
    <p>Analytic: {{ $route.query.q }}</p>
    <hr>
    <button class="btn btn-danger">Confirm</button>
  </div>
</template>

<script>
export default {
}
</script>

<style >
</style>
