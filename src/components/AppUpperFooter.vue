<script>
export default {
    name: 'AppUpperFooter'
}
</script>



<template>
    <div class="upper-footer small-container">
        <div class="upper-footer-col">
            <div>
                <h4>DC COMICS</h4>
                <ul class="mt-20">
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
            <div>
                <h4>SHOP</h4>
                <ul class="mt-20">
                    <li>Shop DC</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
        </div>

        <div class="upper-footer-col">
            <div>
                <h4>DC</h4>
                <ul class="mt-20">
                    <li>Terms Of Use</li>
                    <li>Privacy policy(New)</li>
                    <li>Ad Choice</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
        </div>

        <div class="upper-footer-col">
            <div>
                <h4>SITES</h4>
                <ul class="mt-20">
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
    </div>
</template>



<style>
.upper-footer {
    display: flex;
    height: calc(100% - 100px);
    gap: 50px;
}

.upper-footer-col {
    display: flex;
    flex-direction: column;
    color: #5F6A6C;
    padding: 30px 0px;
    gap: 20px;
}

h4 {
    color: white;
}
</style>