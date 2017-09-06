<template>
  <div id="app">
    <header>
    <h1>Ivan Tadeo Huerta</h1>
    </header>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Hola mundo!'
    }
  }
}
</script>

<style lang="scss" scoped>
  header{
    background-color : green
  }
</style>
