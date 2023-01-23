<script>
export default {
    name: 'AppFooterBottom'
}
</script>

<template>
    <footer>
        <div class="footer-bottom">
            <div class="container">
                <div class="sign-up">
                    <a href="#">SIGN UP NOW</a>
                </div>
                <div class="social">
                    <h3>FOLLOW US</h3>
                    <ul>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.footer-bottom {
    background-color: #303030;
    position: fixed;
    bottom: 0;
    right: 0;
    left: 0;

}

.container {
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.sign-up a {
    color: white;
    text-transform: uppercase;
    padding: 8px;
    border: 1px solid #0282F9;


}

.social {
    display: flex;
    align-items: center;
}

.social ul {
    display: flex;
}

.social li {
    padding: 0 5px;
}

.social h3 {
    color: #0282F9;
    padding: 0 10px;
}
</style>