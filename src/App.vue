<template>
  <v-app>
    <v-content transition="slide-x-transition">
      <AppNavigation v-if="this.$route.path.substring(1, 10) !== 'welcome'"/>
      <WelcomeNavigation v-if="this.$route.path.substring(1, 10) === 'welcome'"/>
      <router-view></router-view> <!-- Visualization Routes -->
      <Footer />
    </v-content>
  </v-app>
</template>

<script>
  import AppNavigation from './components/AppNavigation.vue';
  import WelcomeNavigation from './components/welcomeNavigation.vue';
  import Footer from './components/Footer.vue';

  export default {
    name: 'App',
    components: {
      AppNavigation,
      WelcomeNavigation,
      Footer
    }
  }
</script>

<style>
</style>