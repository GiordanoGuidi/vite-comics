<script>
export default {
    name: 'AppDcBuy',
    methods: {
        createImagePath(image_name) {
            const url = new URL(`../assets/img/${image_name}`, import.meta.url)
            console.log(url)
            return url.href
        },


    },
    props: {
        buyLinks: Array,
    }
}
</script>



<template>
    <!--DC-FOOTER-->
    <div class="dc-info">
        <div class="info-links small-container">
            <div v-for="link in buyLinks" class="links-card">
                <img :src="createImagePath(link.src)" alt="">
                <a href="#">{{ link.text.toUpperCase() }}</a>
            </div>

        </div>
    </div>
</template>



<style>
.jumbotron {
    height: 150px;
    background-color: greenyellow;
    color: white;
}

.jumbotron-card {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.dc-info {
    height: 100px;
    background-color: #0182F9;
    display: flex;
}

.info-links {
    display: flex;
    padding: 50px 0px;
    gap: 50px;

}


.links-card {
    display: flex;
    align-items: center;
    gap: 10px;

    a {
        color: white;
    }

    img {
        width: 50px;
        height: auto;
    }
}
</style>