<template>
  <div id="app">
    <section class="hero">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">
            <img class="logo" src="./assets/logo.png" width="200">
          </h1>
        </div>
      </div>
    </section>
    <section class="section">
      <router-view/>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="sass">
  @import "../node_modules/bulma/sass/utilities/initial-variables"
  $body-background-color: #F1F3F5
  $body-color: #678
  $card-header-color: #345
  @import "../node_modules/bulma/bulma"
  .logo
    margin: auto
</style>
