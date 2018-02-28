<template>
  <div>
    <router-link to="/">Home</router-link>
    <p>This is an about page</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      message: 'Well, you can play around with this thanks'
    }
  }
}
</script>

<style lang="scss">
  $color: grey;

  p {
    color: $color;
  }
</style>
