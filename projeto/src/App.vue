<template>
  <div id="app">
    <NovoComponent/>
    <TesteIf/>
    <TesteFor/>
    <TesteEvento/>

  </div>
</template>

<script>
import NovoComponent from './components/NovoComponent.vue'
import TesteIf from './components/TesteIf.vue'
import TesteFor from './components/TesteFor.vue'
import TesteEvento from './components/TesteEvento.vue'

export default {
  name: 'App',
  components: {
    NovoComponent,
    TesteIf,
    TesteFor,
    TesteEvento
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
