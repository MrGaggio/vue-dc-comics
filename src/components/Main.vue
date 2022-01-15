<template>
  <dir class="jumbo_container">
    <img class="jumbotron" src="../assets/img/jumbotron.jpg" alt="">
  </dir>
</template>

<script>
export default {
name: "Main",
}
</script>

<style lang="scss">
.jumbo_container {
  margin: 0;
  padding: 0;
}

  .jumbotron {
    width: 100%;
    object-fit: cover;
    height: 600px;
    object-position: top;
  }

</style>