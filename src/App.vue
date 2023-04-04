<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
      <HeaderView/>
    </v-app-bar>
  
    <v-main>
      <HeroView/>
    </v-main>
  </v-app>
</template>

<script>
import HeaderView from './components/HeaderView';
import HeroView from './components/HeroView';

export default {
  name: 'App',

  components: {
    HeaderView,
    HeroView
  },

  data: () => ({
    //
  }),
};
</script>
