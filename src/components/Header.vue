<template>
  <div class="header">
    <br>
    <p class="h1">Tom Robertson</p>
    <small class="text-muted">Newcastle University Masters Student</small>
    <br>
    <br>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  background-color: #8de1fa;
  padding-top: 20px;
  padding-bottom: 20px;
}
</style>
