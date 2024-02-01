<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]
    })
}
</script>

<template>
    <header>
        <nav class="small-container">
            <img src="../assets/img/dc-logo.png" alt="">
            <ul class="links-list">
                <li v-for="(link, i) in links" :key="i"><a :href=link.url>{{ link.text }}</a></li>
            </ul>
        </nav>
    </header>
</template>

<style>
header {
    height: 150px;
    background-color: white;
}

header nav {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.links-list {
    display: flex;
    list-style: none;
    gap: 20px;
    height: 100%;
    align-items: center;
}

.links-list li {
    height: 100%;
    display: flex;
    align-items: center;
}

li a {
    color: gray;
}

.links-list li:hover {
    border-bottom: 4px solid #0182F9;
}
</style>