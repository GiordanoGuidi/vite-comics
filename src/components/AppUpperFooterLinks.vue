<script>
export default {
    name: 'AppUpperFooterLinks',
    props: {
        links: Array,
        title: String,
    }
}
</script >


<template>
    <!--SINGLE LINKS LIST CREATE DYNAMICALLY-->
    <h4>{{ title.toUpperCase() }}</h4>
    <ul>
        <li v-for="link in links">
            <a :href="link.url">{{ link.text }}</a>
        </li>
    </ul>
</template>

<style lang="scss" scoped>
a {
    color: #5F6A6C;

    &:hover {
        filter: brightness(100);
    }
}

h4 {
    color: white;
    margin-bottom: 10px;
}
</style>