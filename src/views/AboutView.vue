<template>
  <Navbar />
  <AboutPage />
</template>

<script>
import { defineComponent } from 'vue';

// Components
import AboutPage from '../components/AboutPage.vue';
import Navbar from '../components/comp/navbar.vue';

export default defineComponent({
  name: 'Aboutview',

  components: {
    AboutPage,
    Navbar,
  },
});
</script>
