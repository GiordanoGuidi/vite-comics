
<script>
export default {
    name: 'AppJumbotron',
    props: {

    }

}

</script>


<template>
    <div class="jumbotron">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>

<style>
.jumbotron {
    height: 400px;


    img {
        object-fit: cover;
        object-position: top;
        width: 100%;
        height: 100%;
    }
}
</style>