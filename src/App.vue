<template>
  <v-app>


    <v-content>
      <AppNavigation/>
    </v-content>
  </v-app>
</template>

<script>
import AppNavigation from './components/AppNavigation';

export default {
  name: 'App',

  components: {
    AppNavigation,
  },

  data: () => ({
    //
  }),
};
</script>
