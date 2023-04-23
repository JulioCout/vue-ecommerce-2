<template>
  <v-app>
    <Navbar class="index" />
    <Dashboard class="dash" />
    <Footer class="foot" />
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar-comp.vue';
import Dashboard from '@/components/Dashboard-comp.vue';
import Footer from '@/components/Footer-comp.vue';


  export default {
    name: 'HomeView',

    components: {
    Navbar,
    Dashboard,
    Footer
},
  }
</script>

<style>
.index{
  z-index: 2;
}

.dash {
  z-index: 1;
}

.foot {
  z-index: 1;
}
</style>