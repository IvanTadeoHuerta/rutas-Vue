<template>
  <div id="app">
    <header>
    <h1>Ivan Tadeo Huerta</h1>
    </header>
    <router-link to="/">Home</router-link>
    <router-link to="/editar">editar</router-link>
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
