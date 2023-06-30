<script>
export default {
    props: {
        dcSeries: Array,
    }
}
</script>

<template>
    <div v-for="serie in dcSeries" class="card">
        <div>
            <img :src="serie.thumb" :alt="serie.series">
        </div>
        <h3>{{ serie.series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
.card {
    flex-basis: calc(100% / 6);
    margin: 30px 0;

    div {
        overflow: hidden;
        width: 100%;
        height: 200px;
        padding: 5px;
    }
}

img {
    object-fit: cover;
}

img:first-child {}

h3 {
    color: white;
    padding-top: 10px;
}
</style>