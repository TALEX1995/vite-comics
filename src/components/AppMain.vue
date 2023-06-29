<script>
export default {
    data() {
        return {

        }
    },

}
</script>

<template>
    <main>
        <div class="container">
            <h1>Content Goes Here </h1>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/mixins' as *;
@use '../assets/scss/vars' as *;

main {
    background-color: $background-color-main;
    height: 120px;
}

.container {
    height: 100%;
    @include flexbox (start, center);
}

h1 {
    color: white;
}
</style>