<template>
  <div>
    <h1>Vuelve a intentarlo bitch</h1>
    <p>{{ route }}</p>
  </div>
</template>

<script>
export default {
  computed: {
    route () {
      return this.$route.path
    }
  }
}
</script>

<style>

</style>
