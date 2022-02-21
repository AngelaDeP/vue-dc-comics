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
      </footer>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyContent from './components/MyContent.vue'
import MyLinks from './components/MyLinks.vue'
import MyTopFooter from './components/MyTopFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyLinks,
    MyTopFooter
  }
}
</script>

<style lang="scss">
  @import "./assets/style/general.scss";
</style>

