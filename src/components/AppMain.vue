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
        <button class="load">LOAD MORE</button>
        <ul class="cards-list">
            <AppComicsCard :comicBook="comicBook" />
        </ul>
    </div>
</template>

<style>
.card-container {
    display: flex;
    padding-top: 30px;
    position: relative;
    padding-bottom: 70px;
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

.cards-list {
    display: flex;
    list-style: none;
    flex-wrap: wrap;
    margin-bottom: 20px;

    .comic-book-card {
        flex-basis: calc(100% / 6);
    }
}
</style>