<template>
    <Navbar />
    <FrontPage />
  </template>
  
  <script>
  import { defineComponent } from 'vue';
  
  // Components
  import FrontPage from '../components/FrontPage.vue';
  import Navbar from '../components/comp/navbar.vue';
  
  export default defineComponent({
    name: 'Frontview',
  
    components: {
      FrontPage,
      Navbar,
    },
  });
  </script>
  