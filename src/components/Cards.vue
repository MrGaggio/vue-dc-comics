<template>
  <dir>
    <div class="comic">
      <img 
      :src="src"
      :alt="alt">
      <h3>{{ titolo }}</h3>
      </div>
  </dir>
</template>

<script>
export default {
name: "Cards",
props: {
  src: String,
  titolo: String,
  alt: String,
}
}
</script>

<style lang="scss">


</style>