<template>
  <div id="app">
    
      <Estilito></Estilito>
    <HelloWorld />
  
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import estilito from './store/estilito.css'
export default {
  name: 'App',
  components: {
    HelloWorld,
    estilito
  }
}
</script>

<style>

</style>
