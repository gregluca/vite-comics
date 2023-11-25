<script>
export default {
    props: {
        series: String,
        thumb: String,
        type: String
    },
}
</script>

<template>
    <div class="card">
        <div class="card">
    <img :src="thumb" alt="foto">
    <h3>{{ series }}</h3>
  </div>
    </div>

</template>

<style scoped lang="scss">
    .card {
    height: 100%;

    img {
        height: 200px;
        width: 200px;
    }
}
</style>