<script>
import AppHeader from './components/AppHeader.vue'
import AppUpperFooter from './components/AppUpperFooter.vue'
import AppBottomFooter from './components/AppBottomFooter.vue'
import AppDcInfo from './components/AppDcInfo.vue'





export default {
  name: 'vite-comics',

  components: {
    AppHeader, AppUpperFooter, AppBottomFooter, AppDcInfo,


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
      <AppDcInfo />
    </main>

    <!--FOOTER-->
    <footer>
      <!--UPEER FOOTER-->
      <AppUpperFooter />
      <AppBottomFooter />
    </footer>
  </div>
</template>

<style lang="scss">
@use './assets/scss/style.scss';
</style>
