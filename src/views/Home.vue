<template>
  <v-app>
    <Navbar class="index" />
    <Dashboard />
    <Footer />
  </v-app>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Dashboard from '../components/Dashboard'
  import Footer from '../components/Footer'

  export default {
    name: 'Home',

    components: {
      Navbar,
      Dashboard,
      Footer

    },
  }
</script>
<style scoped>
.index{
  z-index: 9999;
}
</style>
