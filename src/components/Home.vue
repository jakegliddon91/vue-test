<template>
  <div class="home">
    <section class="hero is-medium hero-1 hero-head">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Jake Gliddon Web Development
          </h1>
          <h2 class="subtitle is-two-thirds">
            Whether it's Front-end or Back-end Development I've got your back
          </h2>
        </div>
      </div>
    </section>
    
  </div>
</template>

<script>
export default {
  name: 'home',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'
.hero-1
  background-color: red
  .title
    color: yellow
  .subtitle
    color: yellow

</style>
