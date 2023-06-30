<script>
import ComicCard from './ComicCard.vue'
export default {
    props: {

    },
    components: {
        ComicCard,
    }

}
</script>

<template>
    <main>
        <div class="container">
            <ComicCard />
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
    @include flexbox (start, center);
    flex-wrap: wrap;
}

h1 {
    color: white;
}

.card {
    flex-basis: calc(100% / 6);
}
</style>