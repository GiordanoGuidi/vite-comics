<script>
export default {
    name: 'AppUpperFooter',
    props: {
        links: Array
    }
}
</script>



<template>
    <!--UPPER FOOTER-->
    <div class="upper-footer small-container">
        <!--COL-->
        <div class="col" v-for="(link, i) in links" :key="i">
            <h4>{{ link.title.toUpperCase() }}</h4>
            <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>
        </div>
        <div class="bg-footer">
            <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<style lang="scss" scoped>
.upper-footer {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    height: calc(100% - 200px);
    position: relative;

    .col {
        flex-direction: column;
        padding: 30px 0px;
        margin-right: 30px;

        a {
            color: #5F6A6C;

            &:hover {
                filter: brightness(100);
            }
        }

    }
}

.bg-footer {
    width: 100%;
    overflow: hidden;
    // position: relative;

    img {
        position: absolute;
        right: 0;
        top: -80px;
    }
}

.p-0 {
    padding: 0px;
}



h4 {
    color: white;
}
</style>