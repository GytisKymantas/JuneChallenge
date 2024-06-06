<template>
  <HeaderHero />
  <MainHero />
  <FooterHero />
</template>

<script>
import HeaderHero from './components/HeaderHero.vue';
import FooterHero from './components/FooterHero.vue';
import MainHero from './components/MainHero.vue';

export default {
  name: 'App',
  components: {
    HeaderHero,
    FooterHero,
    MainHero,
  },
};
</script>

<style>
html {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
*,
*::after,
*::before {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
