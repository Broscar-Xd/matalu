<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <alumnos></alumnos>
    <principal></principal>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import alumnos from './components/alumnos.vue'
import Principal from './components/principal.vue'


export default {
  name: 'App',
  components: {
    alumnos,
    Principal
    
  }
}
</script>
