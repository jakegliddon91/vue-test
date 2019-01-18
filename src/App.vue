<template>
  <div id="app">
      <nav class="navbar has-shadow" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <div class="navbar-item">
            Jake Gliddon
            </div>
        </div>

            <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-end">
            
            <router-link to="/" class="navbar-item">
              Home
            </router-link>

            <router-link to="/about" class="navbar-item">
              About
            </router-link>

            <router-link to="/portfolio" class="navbar-item">
              Portfolio
            </router-link>

            <router-link to="/contact" class="navbar-item">
              Contact
            </router-link>            
          </div>
        </div>
      </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import 'mq'
#app
  background-color: #800000
.navbar
  background-color: red
  margin-bottom: 0
  .navbar-brand
    .navbar-item
      color: yellow
    font-weight: bold
  .navbar-menu
    .navbar-item
      padding-right: 40px
      color: yellow

</style>
