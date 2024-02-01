<script>
import AppHeader from './components/AppHeader.vue'
import AppUpperFooter from './components/AppUpperFooter.vue'


export default {
  name: 'vite-comics',

  components: {
    AppHeader, AppUpperFooter


  }

}
</script>

<template>
  <div class="main-container">
    <!--HEADER-->
    <AppHeader />

    <main>
      <!--JUMBOTRON-->
      <div class="jumbotron">
        <div class="jumbotron-card small-container">
          <p>--Content goes here--</p>
        </div>
      </div>
      <!--BONUS-->
      <div class="dc-info">
        <div class="info-links small-container">
          <div class="links-card">
            <img src="../src/assets/img/buy-comics-digital-comics.png" alt="">
            <p>DIGITAL COMICS</p>
          </div>
          <div class="links-card">
            <img src="../src/assets/img/buy-comics-merchandise.png" alt="">
            <p>DIGITAL COMICS</p>
          </div>
          <div class="links-card">
            <img src="../src/assets/img/buy-comics-shop-locator.png" alt="">
            <p>DIGITAL COMICS</p>
          </div>
          <div class="links-card">
            <img src="../src/assets/img/buy-comics-subscriptions.png" alt="">
            <p>DIGITAL COMICS</p>
          </div>
          <div class="links-card">
            <img src="../src/assets/img/buy-dc-power-visa.svg" alt="">
            <p>DIGITAL COMICS</p>
          </div>
        </div>
      </div>
    </main>
    <!--FOOTER-->
    <footer>
      <!--UPEER FOOTER-->
      <AppUpperFooter />

      <div class="bottom-footer">
        <div class="small-container">
          <div class="bottom-footer-info">

            <a href="">SIGN UP NOW!</a>
            <div class="d-flex align-center">
              <span>FOLLOW US</span>
              <ul class="icon-list">
                <li>
                  <a href="#">
                    <img src="../src/assets/img/footer-facebook.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../src/assets/img/footer-periscope.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../src/assets/img/footer-pinterest.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../src/assets/img/footer-twitter.png" alt="">
                  </a>
                </li>
                <li>
                  <a href="#">
                    <img src="../src/assets/img/footer-youtube.png" alt="">
                  </a>
                </li>


              </ul>
            </div>

          </div>
          <div>

          </div>
        </div>

      </div>

    </footer>

  </div>
</template>

<style>
/*CSS RESET*/
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

/*UTILS*/
.mt-20 {
  margin-top: 20px;
}

/*GENERICS*/
.main-container {
  margin: 50px 0px;
}

.small-container {
  width: 70%;
  margin: 0 auto;
}

ul li {
  list-style: none;
}

.d-flex {
  display: flex;

}

.align-center {
  align-items: center;
}

li a {
  text-decoration: none;
}

/*MAIN*/
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
  background-color: lightblue;
  display: flex;
}

.info-links {
  display: flex;
  padding: 50px 0px;
  gap: 20px;
}

.info-links img {
  width: 50px;
}

.links-card {
  display: flex;
  align-items: center;
  gap: 10px;
}

/*FOOTER*/
footer {
  height: 500px;
  background-image: url(../src/assets/img/footer-bg.jpg);
}


.bottom-footer {
  height: 100px;
  background-color: cadetblue;
  display: flex;
  align-items: center;
}

.bottom-footer-info {
  display: flex;
  justify-content: space-between;
}

.icon-list {
  display: flex;
  align-items: center;
  list-style: none;
}
</style>
