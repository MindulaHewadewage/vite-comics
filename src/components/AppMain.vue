<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <main>
        <section class="content">
            <div class="container card-container">

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

                <div class="card-container">
                    <div class="comic-card">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="">
                        <h3>action comics</h3>
                    </div>
                </div>

            </div>

        </section>
        <section class="merchandise"></section>
    </main>

</template>

<style lang="scss" scoped>
// content
.content {
    background-color: #1C1C1C;
    color: white;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    flex-basis: calc(100% / 6);
    padding: 20px 0;
}



.comic-card img {

    object-fit: cover;
    height: 150px;
    width: 150px;

}

.comic-card h3 {
    text-transform: uppercase;
    font-size: 13px;
    padding: 10px 0;
}


// merchandise
.merchandise {
    min-height: 100px;
    background-color: #0282F9;
}
</style>