<template>
    <NavBar/>
    <Contact/>
    <Footer/>
    </template>
    
    <script>
    import NavBar from '../components/NavBar.vue';
    import Footer from '../components/Footer.vue';
    import Contact from '../components/ContactForm.vue'
    export default {
        components: {
            NavBar, Footer, Contact
        }
        
    }
    </script>
    
    <style>
        
    </style>