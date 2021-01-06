<template>
 <v-app>
   <NavBar />
   <Home />
   <Footer />
 </v-app>
</template>

<script>

import NavBar from './components/NavBar';
import Home from'./components/HomePage';
import Footer from'./components/Footer';
export default {
  name: 'App',

  components: {
    NavBar,
    Home,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
