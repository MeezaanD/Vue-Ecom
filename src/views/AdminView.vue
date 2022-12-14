<template>
    <NavBar/>
    <Admin/>
    <Footer/>
    </template>
    
    <script>
    import NavBar from '../components/NavBar.vue';
    import Footer from '../components/Footer.vue';
    import Admin from '../components/AdminTable.vue';
    export default {
        components: {
            NavBar, Footer, Admin
        }
        
    }
    </script>
    
    <style>
        
    </style>