<script>
</script>

<template>
    <footer>
        <div class="container">
            <div>
                <button>
                    SIGN-UP NOW!
                </button>
            </div>
            <div class="footer-right">
                <h2>FOLLOW US</h2>
                <ul>
                    <li><img src="../assets/img/footer-facebook.png" alt="fb"></li>
                    <li><img src="../assets/img/footer-twitter.png" alt="tw"></li>
                    <li><img src="../assets/img/footer-youtube.png" alt="tw"></li>
                    <li><img src="../assets/img/footer-periscope.png" alt="tw"></li>
                    <li><img src="../assets/img/footer-pinterest.png" alt="tw"></li>
                </ul>
            </div>

        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/mixins' as *;
@use '../assets/scss/vars' as *;

footer {
    background-color: $footer-bot-bg-color;
}

button {
    padding: 10px;
    background-color: transparent;
    border: 1px solid $lightblue;
    color: white;
    margin: 15px 0;
    cursor: pointer;
}

.container {
    @include flexbox (space-between);
}

.footer-right {
    display: flex;
}

h2 {
    color: $lightblue;
}

ul {
    display: flex;

    li {
        margin: 0 10px;
    }
}
</style>