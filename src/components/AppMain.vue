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
        <div class="container">
            <ComicCard :dcSeries="dcSeries" />
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/mixins' as *;
@use '../assets/scss/vars' as *;

main {
    background-color: $background-color-main;
}

.container {
    @include flexbox (center, baseline);
    flex-wrap: wrap;
}

h1 {
    color: white;
}
</style>