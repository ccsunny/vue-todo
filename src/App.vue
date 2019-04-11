<template>
  <div id="app">
    <div id="cover"></div>
    <Header />
    <TodoList />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header'
import TodoList from './components/TodoList'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Header,
    TodoList,
    Footer
  }
}
</script>

<style lang="less">
#app {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  #cover{
    position: absolute;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    background-color: #999;
    opacity: .9;
    z-index: -1;
  }
}
</style>
