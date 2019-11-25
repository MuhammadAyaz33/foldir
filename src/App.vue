<template>
  <div id="app">
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Footer from './components/Footer';
export default {
  name: 'app',
   components: {
    Footer
  }
};
</script>

<style>
#app {
    background-color: #eae8e863;
}

</style>
