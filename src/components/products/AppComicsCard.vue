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
    <li class="comic-book-card" v-for="book in comicBook">
        <a :href="book.series">
            <img :src=book.thumb :alt="book.series">
        </a>
        <h3>{{ book.series }}</h3>
    </li>
</template>

<style>
h3 {
    color: white;
    font-size: 0.8rem;
}

.comic-book-card {
    padding: 10px;

    img {
        height: 70%;
        width: 100%;
    }
}
</style>