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
                        <ul class="comics">
                            <li><a href="#" class="cat-title">DC COMICS</a></li>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <ul class="comics">
                            <li><a href="#" class="cat-title">SHOP</a></li>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>



                </nav>
                <!-- <figure>
                    <a href=" #"><img src="../assets/img/dc-logo-bg.png" alt="logo dc"></a>
                </figure> -->
            </div>
        </section>




    </footer>
</template>

<style scoped>
.footer-top {
    min-height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
}

nav .cat-title {
    color: white;
    font-size: 20px;
}

nav a {
    color: grey;
}
</style>