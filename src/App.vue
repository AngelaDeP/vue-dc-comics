<template>
  <div id="app">
      <header>
        <MyHeader/>
      </header>
      <main>
        <MyContent/>
        <MyLinks/>
      </main>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyContent from './components/MyContent.vue'
import MyLinks from './components/MyLinks.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyLinks
  }
}
</script>

<style lang="scss">
  @import "./assets/style/general.scss";
</style>

