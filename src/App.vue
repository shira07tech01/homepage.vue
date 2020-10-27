<template>
  <div id="app">
    <web-header />
    <web-content />
    <web-footer />
  </div>
</template>

<script>
import header from './components/header.vue'
import footer from './components/footer.vue'
import content from './components/content.vue'

export default {
  name: 'App',
  components: {
    'web-header': header,
    'web-footer': footer,
    'web-content': content
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
