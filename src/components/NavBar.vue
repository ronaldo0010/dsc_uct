<template>
  <div>
    <b-navbar type="dark" variant="primary">
      <b-navbar-brand href="#">Developer Student Club UCT</b-navbar-brand>
      <b-navbar-nav class="ml-auto">
        <b-nav-item >Events</b-nav-item>
        <b-nav-item>Mentors</b-nav-item>
        <b-nav-item>Projects</b-nav-item>
        <b-nav-item>About</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
    
  </div>
</template>

<script>
import { BNavbar} from 'bootstrap-vue'

    export default {
    name: 'NavBar',
    components: {
      BNavbar, 
    }
}
</script>

<style scoped>
  
</style>