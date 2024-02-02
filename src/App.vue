<script>
import AppHeader from './components/AppHeader.vue'
import AppUpperFooter from './components/AppUpperFooter.vue'
import AppBottomFooter from './components/AppBottomFooter.vue'
import AppDcInfo from './components/AppDCInfo.vue'





export default {
  name: 'vite-comics',

  data: () => ({

    footerBuyLinks: [
      {
        id: 1,
        text: 'digital comics',
        src: 'buy-comics-digital-comics.png'
      },
      {
        id: 2,
        text: 'dc merchandise',
        src: 'buy-comics-merchandise.png'
      },
      {
        id: 3,
        text: 'subscription',
        src: 'buy-comics-subscriptions.png'
      },
      {
        id: 4,
        text: 'comic shop locator',
        src: 'buy-comics-shop-locator.png'
      },
      {
        id: 5,
        text: 'dc power visa',
        src: 'buy-dc-power-visa.svg'
      }
    ]

  }),

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
    </main>

    <!--FOOTER-->
    <footer>
      <!--BONUS-->
      <AppDcInfo :buyLinks="footerBuyLinks" />
      <!--UPEER FOOTER-->
      <AppUpperFooter />
      <AppBottomFooter />
    </footer>
  </div>
</template>

<style lang="scss">
@use './assets/scss/style.scss';
</style>
