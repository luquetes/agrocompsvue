<template>
  <div id="app">
    <montserrat />
    <AgroHeaderTabs />
    <AgroHeader />
    <h1>Agrofy UI Components - Vue</h1>
    <router-view></router-view>
    <Footer />
  </div>
</template>

<script>

import {Montserrat400} from 'agrofy-ui-components'
import AgroHeaderTabs from './components/AgroHeaderTabs.vue'
import AgroHeader from './components/AgroHeader.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    'montserrat' : Montserrat400,
    'Footer' : Footer,
    'AgroHeaderTabs' : AgroHeaderTabs,
    'AgroHeader' : AgroHeader
  }
}
</script>

<style>
  body {
    padding: 0;
    margin: 0;
  }
</style>


