<script>
import AppComicsCard from './products/AppComicsCard.vue'
export default {
    name: 'AppMain',
    props: {
        comicBook: Array
    },
    components: {
        AppComicsCard
    }
}

</script>


<template>
    <!--CARDS-CONTAINER-->
    <div class="small-container card-container">
        <AppComicsCard :comicBook="comicBook" />
    </div>
</template>

<style>
.card-container {
    display: flex;
    flex-wrap: wrap;
    padding-top: 30px;
}

.comic-book-card {
    flex-basis: calc(100% / 6);
    padding: 10px;
}
</style>