<script>
import ComicCard from './ComicCard.vue'
export default {
    props: {
        dcSeries: Array
    },
    components: {
        ComicCard,
    }

}
</script>

<template>
    <main>
        <div class="jumbo">
            <img class="dc-hero" src="https://fumettologica.it/wp-content/uploads/2021/03/infinite-frontier-dc.jpg"
                alt="Hero">
        </div>
        <div class="container">
            <div class="current-series">Current Series</div>
        </div>
        <div class="container card-container">
            <ComicCard :dcSeries="dcSeries" />
            <button>Load More</button>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/mixins' as *;
@use '../assets/scss/vars' as *;

main {
    background-color: $background-color-main;
    position: relative
}

.card-container {
    @include flexbox (center, baseline);
    flex-wrap: wrap;
}

h1 {
    color: white;
}

.dc-hero {
    width: 100%;
}

button {
    padding: 10px 60px;
    background-color: $lightblue;
    color: white;
    border: none;
    margin-bottom: 20px;
}

.current-series {
    background-color: $lightblue;
    color: white;
    width: 150px;
    text-align: center;
    line-height: 40px;
    position: absolute;
    margin-top: -20px;
}

.jumbo {
    height: 300px;
    overflow: hidden;
}
</style>