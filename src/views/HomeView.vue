<template>
<NavBar/>
    <HelloWorld/>
<Footer/>    
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import NavBar from '../components/NavBar.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld, NavBar, Footer
  }
}
</script>
