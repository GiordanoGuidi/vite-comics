<script>
export default {
    name: 'AppComicsCard',
    props: {
        comicBook: Array
    }

}

</script>


<template>
    <!--SINGLE-CARD-->
    <div class="comic-book-card" v-for="book in comicBook">
        <img :src=book.thumb alt="">
        <h3>{{ book.series }}</h3>
    </div>
</template>

<style>
h3 {
    color: white;
    font-size: 0.8rem;
}

img {
    max-width: 100%;
    height: 70%;
}
</style>