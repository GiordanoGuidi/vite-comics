<script>
export default {
    name: 'AppDcInfo'
}
</script>



<template>
    <div class="dc-info">
        <div class="info-links small-container">
            <div class="links-card">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="links-card">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="links-card">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="links-card">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="links-card">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DIGITAL COMICS</p>
            </div>
        </div>
    </div>
</template>



<style>
.jumbotron {
    height: 150px;
    background-color: black;
    color: white;
}

.jumbotron-card {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.dc-info {
    height: 200px;
    background-color: #0182F9;
    display: flex;
}

.info-links {
    display: flex;
    padding: 50px 0px;
    gap: 50px;
}

.info-links img {
    width: 50px;
    height: auto;
}

.links-card {
    display: flex;
    align-items: center;
    gap: 10px;
    color: white;
}
</style>