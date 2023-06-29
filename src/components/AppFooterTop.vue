<script>

</script>

<template>
    <footer>
        <div class="container">
            <div>
                <h2>DC Comics</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <h2>Shop</h2>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="footer-middle-row">
                <h2>DC</h2>
                <ul>
                    <li><a href="#">Terms of use</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Ad choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contac Us</a></li>
                </ul>
            </div>
            <div>
                <h2>Sites</h2>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">Mad Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {
    padding: 40px 0;
    background-image: url(../assets/img/dc-logo-bg.png), url(../assets/img/footer-bg.jpg);
    background-position: 80% 50%;
    background-repeat: no-repeat;
    background-size: auto, cover;
}

h2 {
    color: white;
    margin-bottom: 15px;
}

a {
    color: #807266;
}

ul+h2 {
    margin-top: 15px;
}

.container {
    display: flex;
}

.footer-middle-row {
    margin: 0 30px;
}
</style>