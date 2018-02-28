<template>
  <div>
    <header class="hero is-primary is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-1">EEy</h1>
          <p class="subtitle is-3">??</p>
        </div>
      </div>
    </header>
    <router-link to="/about">About</router-link>
    <p>{{ message }}</p>
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

yep
yep, thank np you
