<script>
import AppHeader from './components/AppHeader.vue';
import AppBodyList from './components/AppBodyList.vue';
import AppFooter from './components/AppFooter.vue';
import AppBonus from './components/AppBonus.vue';


export default {
  components: {
    AppHeader,
    AppBodyList,
    AppFooter,
    AppBonus
  }
}
</script>

<template>
  <AppHeader />
  <AppBodyList />
  <AppBonus />
  <AppFooter /> 
  
</template>

<style lang="scss">
@use "./style/general.scss";
</style>
