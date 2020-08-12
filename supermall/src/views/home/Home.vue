<template>
  <div id="home">
    <nav-bar class="home"><div slot="center">购物街</div></nav-bar>
  </div>
</template>

<script>
import NavBar from '../../components/common/navbar/NavBar'
export default {
  name: 'Home',
  components: {
    NavBar
  }
}
</script>

<style>
  .home {
    text-align: center;
    color: #fff;
    background-color: pink;
  }
</style>