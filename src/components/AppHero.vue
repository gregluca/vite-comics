<script>
export default {

}
</script>
<template>
<div class="hero"></div>
</template>
<style scoped lang="scss">
@use "../style/partials/variables" as *;
@use "../style/partials/mixin" as *;

.hero {
    background-image: url('../assets/img/jumbotron.jpg');
    height: 250px;
    background-size: cover;
    width: 100%;
}
</style>