<script>
import AppHeader from './components/AppHeader.vue';
import AppBodyList from './components/AppBodyList.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  components: {
    AppHeader,
    AppBodyList,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />
  <AppBodyList />
  <AppFooter /> 
  
</template>

<style lang="scss">
@use "./style/general.scss";
</style>
