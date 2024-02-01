<script>
</script>

<template>
  <div class="main-container">
    <header>
      <nav>
        <img src="../src/assets/img/dc-logo.png" alt="">
        <ul class="links-list">
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
          <li>Ciao be</li>
        </ul>
      </nav>
    </header>
    <main>
      <!--JUMBOTRON-->
      <div class="jumbotron">
        <div class="jumbotron-card">
          <p>--Content goes here--</p>
        </div>
      </div>
      <!--BONUS-->
      <div class="dc-info">
        <div class="info-links">
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



/*GENERICS*/

header {
  height: 150px;
  background-color: forestgreen;
}

.main-container {
  margin: 50px 0px;
}

/*HEADER*/
header nav {
  width: 70%;
  margin: 0 auto;
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

/*MAIN*/
.jumbotron {
  height: 150px;
  background-color: black;
  color: white;
}

.jumbotron-card {
  width: 70%;
  height: 100%;
  margin: 0 auto;
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
  width: 70%;
  margin: 0 auto;
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
</style>
