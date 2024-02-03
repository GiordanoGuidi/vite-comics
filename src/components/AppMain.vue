<script>
import AppComicsCard from './products/AppComicsCard.vue'
export default {
    name: 'AppMain',
    props: {
        comicBook: Array
    },
    components: {
        AppComicsCard,
    }
}

</script>


<template>
    <!--CARDS-CONTAINER-->
    <div class="small-container card-container">
        <button class="series">CURRENT SERIES</button>
        <AppComicsCard :comicBook="comicBook" />
        <button class="load">LOAD MORE</button>
    </div>
</template>

<style>
.card-container {
    display: flex;
    flex-wrap: wrap;
    padding-top: 30px;
    position: relative;
}

.comic-book-card {
    flex-basis: calc(100% / 6);
    padding: 10px;
}

button {
    color: white;
    font-weight: 800;
    background-color: #0182F9;
    border: 0;
}

button.series {
    position: absolute;
    top: -15px;
    padding: 10px;
}

button.load {
    position: absolute;
    padding: 10px 40px;
    bottom: 0;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>