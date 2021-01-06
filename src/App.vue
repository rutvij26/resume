<template>
 <v-app>
   <NavBar />
   <Home />
 </v-app>
</template>

<script>

import NavBar from './components/NavBar';
import Home from'./components/HomePage';

export default {
  name: 'App',

  components: {
    NavBar,
    Home
  },

  data: () => ({
    //
  }),
};
</script>
