<script>
export default {
    data() {
        return {
            navBarLinks: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]

        }
    }
}
</script>

<template>
    <header class="container">
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <li v-for="link in navBarLinks" :key="link.text">
                    <a href="link.url" :class="{ active: link.current }">
                        {{ link.text }}
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>


<style lang="scss" scoped>
@use '../assets/scss/mixins' as *;
@use '../assets/scss/vars' as *;

header {
    height: 120px;
    @include flexbox (space-between);
}

div {
    height: 100%;
    @include flexbox();
}

img {
    height: 80px;
}

ul {
    @include flexbox;

    a {
        color: black;
        padding: 10px;
        font-weight: bold;

        &.active {
            color: $lightblue;
            border-bottom: 3px solid $lightblue;
        }
    }
}
</style>