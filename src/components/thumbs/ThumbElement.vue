<script>
export default {
    name: 'ThumbElement',
    props: {
        thumb: Object
    }
}
</script>


<template>
    <div class="comic-card">
        <img :src="thumb.thumb" :alt="thumb.series">
        <h3>{{ thumb.series }}</h3>
    </div>

</template>

<style>
.comic-card img {

    object-fit: cover;
    height: 150px;
    width: 150px;

}

.comic-card h3 {
    text-transform: uppercase;
    font-size: 13px;
    padding: 10px 0;
    color: lightgrey;
}
</style>