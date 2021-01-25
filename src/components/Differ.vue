<template>
  <div class="grid grid-cols-2">
    <div class="relative">
      <h2>File 1</h2>
    </div>
    <div class="relative">
      <h2>File 2</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    file1: String,
    file2: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
