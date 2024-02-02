<script>
export default {
    name: 'AppUpperFooter'
}
</script>



<template>
    <!--UPPER FOOTER-->
    <div class="upper-footer small-container">
        <!--COL-->
        <div class="col">
            <div>
                <h4>DC COMICS</h4>
                <ul class="mt-20">
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
            </div>
            <div>
                <h4>SHOP</h4>
                <ul class="mt-20">
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
        </div>
        <!--COL-->
        <div class="col">
            <div>
                <h4>DC</h4>
                <ul class="mt-20">
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy(New)</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
        </div>
        <!--COL-->
        <div class="col">
            <div>
                <h4>SITES</h4>
                <ul class="mt-20">
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.upper-footer {
    display: flex;
    height: calc(100% - 200px);
    gap: 50px;

    .col {
        display: flex;
        flex-direction: column;
        padding: 30px 0px;
        gap: 20px;

        a {
            color: #5F6A6C;
        }

        a:hover {
            filter: brightness(100);
        }
    }
}

h4 {
    color: white;
}
</style>