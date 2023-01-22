<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: [
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
};
</script>


<template>
    <header>
        <div class="container">
            <figure>
                <a href=" #"><img src="../assets/img/dc-logo.png" alt="logo dc"></a>
            </figure>
            <nav>
                <ul>
                    <li v-for="link in links" :key="link.text">
                        <a :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>

    </header>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header {
    min-height: 100px;
    background-color: red;
}


ul {
    display: flex;
}


ul li a {
    font-size: 13px;
    padding: 15px;
    text-transform: uppercase;
    color: black;

}

ul li a:hover {
    color: dodgerblue;
    border-bottom: 1px solid dodgerblue;

}
</style>