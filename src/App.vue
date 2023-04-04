<template>
  <v-app>
    <v-app-bar
      app
      flat
    >
      <HeaderView/>
    </v-app-bar>
  
    <v-content>
      <HeroView/>
      <GalleryView/>
      <LatestPosts/>
    </v-content>

    <v-footer>
      <FooterView/>
    </v-footer>
  </v-app>
</template>

<script>
import HeaderView from './components/HeaderView';
import HeroView from './components/HeroView';
import GalleryView from './components/GalleryView';
import LatestPosts from './components/LatestPosts';
import FooterView from './components/FooterView';

export default {
  name: 'App',

  components: {
    HeaderView,
    HeroView,
    GalleryView,
    LatestPosts,
    FooterView,
  },

  data: () => ({
    //
  }),
};
</script>
