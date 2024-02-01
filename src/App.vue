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
</style>
