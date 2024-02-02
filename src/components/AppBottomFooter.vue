<script>
export default {
    name: 'AppBottomFooter'
}
</script>



<template>
    <!--BOTTOM-FOOTER-->
    <div class="bottom-footer">
        <div class="small-container">
            <div class="bottom-footer-info">
                <!--SIGN BUTTON-->
                <a href="" class="fw-bold sign-button">SIGN UP NOW!</a>
                <div class="d-flex align-center">
                    <span class="c-blue">FOLLOW US</span>
                    <!--ICON LIST-->
                    <ul class="icon-list">
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-facebook.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-periscope.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-pinterest.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-twitter.png" alt="">
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/img/footer-youtube.png" alt="">
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.bottom-footer {
    height: 100px;
    background-color: #303030;
    display: flex;
    align-items: center;

    a {
        font-weight: bold;
    }
}

.bottom-footer-info {
    display: flex;
    justify-content: space-between;
}

.icon-list {
    margin-left: 20px;
    display: flex;
    align-items: center;
    list-style: none;
    gap: 10px;
}

.sign-button {
    border: 2px solid #0A80F9;
    color: white;
    text-align: center;
    padding: 15px;
}

.c-blue {
    color: #0A80F9;
}
</style>