<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
    <HeaderView/>
    </v-app-bar>

    <v-main>
    </v-main>
  </v-app>
</template>

<script>
import HeaderView from './components/HeaderView';

export default {
  name: 'App',

  components: {
    HeaderView,
  },

  data: () => ({
    //
  }),
};
</script>
