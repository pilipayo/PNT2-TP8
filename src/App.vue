<template>
  <div class="container-fluid mt-3">
   <div class="jumbotron">
     <h1> FORMULARIO Vuex</h1>
     <hr>
      <NavBar/>
     <router-view></router-view>

   </div>
 </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    
  }
}
</script>

<style>
.jumbotron{
  color: rgb(34, 19, 8);
}
</style>
