<template>
  <v-app>
   <Navbar />

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Navbar from './components/layouts/Navbar'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar
  },
  data: () => ({
    //
  }),
};
</script>
