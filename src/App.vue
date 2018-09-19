
<style>
</style>

<template>
  <div id="app">
    <Slide @validate="validate" />
  </div>
</template>

<script>
import Slide from './components/Slide'

export default {
  name: 'App',
  components: {
    Slide
  },
  methods: {
    validate () {
      console.log('parent function')
    }
  }
}
</script>
