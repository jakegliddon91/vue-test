<template>
  <div id="app">
      <nav class="navbar has-shadow" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <div class="navbar-item">
            Jake Gliddon
            </div>
        </div>

        
        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-end">
            <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>
            
            <router-link to="/" class="navbar-item">
              Home
            </router-link>

            <router-link to="/faq" class="navbar-item">
              About
            </router-link>

            <router-link to="/" class="navbar-item">
              Portfolio
            </router-link>

            <router-link to="/" class="navbar-item">
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
.navbar
  background-color: red
  .navbar-brand
    .navbar-item
      color: yellow
    font-weight: bold
  .navbar-menu
    .navbar-item
      padding-right: 40px
      color: yellow

</style>
