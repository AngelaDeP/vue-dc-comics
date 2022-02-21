<template>
  <div id="app">
      <header>
        <MyHeader/>
      </header>
      <main>
        <MyContent/>
      </main>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyContent from './components/MyContent.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent
  }
}
</script>

<style lang="scss">
  @import "./assets/style/general.scss";
</style>

