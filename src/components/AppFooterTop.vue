<script>
export default {
    name: 'AppFooterTop'
}
</script>

<template>

    <footer>


        <section class="footer-top">
            <div class="container">
                <nav>
                    <div class="comics-shop">
                        <h3>DC COMICS</h3>
                        <ul class="comics-list">
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <h3>SHOP</h3>
                        <ul class="shop-list">
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>

                    <div class="dc">
                        <h3>DC</h3>
                        <ul class="dc-list">
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>

                    <div class="sites">
                        <h3>SITES</h3>
                        <ul class="sites-list">
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>


                </nav>
                <figure>
                    <a href=" #"><img src="../assets/img/dc-logo-bg.png" alt="logo dc"></a>
                </figure>
            </div>
        </section>




    </footer>
</template>

<style scoped>
.footer-top {
    min-height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
}

nav {
    display: flex;
    padding-top: 40px;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}


nav h3 {
    color: white;
    font-size: 20px;
    margin-bottom: 10px;
}

nav a {
    color: grey;
}

nav li {
    padding: 3px 0;
}

ul {
    margin-right: 30px;
}

figure a img {
    width: 300px;
}
</style>