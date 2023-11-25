<script>
import AppHeader from './components/AppHeader.vue';
import AppBodyList from './components/AppBodyList.vue';
import AppFooter from './components/AppFooter.vue';
import AppBonus from './components/AppBonus.vue';
import AppHero from './components/AppHero.vue';


export default {
  components: {
    AppHeader,
    AppBodyList,
    AppFooter,
    AppBonus,
    AppHero
  }
}
</script>

<template>
  <AppHeader />
  <AppHero />
  <AppBodyList />
  <AppBonus />
  <AppFooter /> 

  
</template>

<style lang="scss">
@use "./style/general.scss";
</style>
