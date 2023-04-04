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
      <GalleryView/>
      <LatestPosts/>
    </v-main>
  </v-app>
</template>

<script>
import HeaderView from './components/HeaderView';
import HeroView from './components/HeroView';
import GalleryView from './components/GalleryView';
import LatestPosts from './components/LatestPosts';

export default {
  name: 'App',

  components: {
    HeaderView,
    HeroView,
    GalleryView,
    LatestPosts,
  },

  data: () => ({
    //
  }),
};
</script>
