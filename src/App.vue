<template>
  <div id="app">
      <header>
        <MyHeader/>
      </header>
      <main>
        <MyContent/>
        <MyLinks/>
      </main>
      <footer>
        <MyTopFooter/>
        <MyBottomFooter/>
      </footer>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyContent from './components/MyContent.vue'
import MyLinks from './components/MyLinks.vue'
import MyTopFooter from './components/MyTopFooter.vue'
import MyBottomFooter from './components/MyBottomFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyLinks,
    MyTopFooter,
    MyBottomFooter
  }
}
</script>

<style lang="scss">
  @import "./assets/style/general.scss";
</style>

