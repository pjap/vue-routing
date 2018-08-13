<template>
  <div>
    <h1>Component User Detail</h1>
    <p>User Loaded Has ID : {{ $route.params.id }}</p>
    <router-link
      tag="button"
      :to="{ name: 'userEdit', params: { id:$route.params.id }, query: { locale: 'en', q: 100 } }"
      class="btn btn-primary">Edit User
    </router-link>
  </div>
</template>

<script>
export default {
}
</script>

<style >
</style>
