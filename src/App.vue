<template>
<div class=" p-5" >
  <HelloWorld />

</div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body{
  background-color: #FBDE60 ;
}
#app {
  font-family: Comfortaa, open-sans;
  text-align: left;
  color: #282828;
  margin-top: 60px;
}
</style>
