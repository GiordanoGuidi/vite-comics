<script>
import AppUpperFooterLinks from './AppUpperFooterLinks.vue';
export default {
    name: 'AppUpperFooter',
    components: {
        AppUpperFooterLinks,
    },
    props: {
        linksLists: Array,
    }
}
</script>



<template>
    <!--UPPER FOOTER-->
    <div class="upper-footer small-container">
        <!--COL-->
        <div class="col" v-for="(link, i) in linksLists" :key="i">
            <AppUpperFooterLinks :links="link.links" :title="link.title" />
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

}

.col {
    flex-direction: column;
    padding: 30px 0px;
    margin-right: 30px;


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
</style>