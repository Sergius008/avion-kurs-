<template>
  <div class="main-container">
    <HeaderTop />
    
    <nav class="navi-list">
      <router-link to="/">Plant pots</router-link> |
      <router-link to="/about">Ceramics</router-link>
      <router-link to="/about">Tables</router-link>
      <router-link to="/about">Chairs</router-link>
      <router-link to="/about">Crockery</router-link>
      <router-link to="/about">Tableware</router-link>
      <router-link to="/about">Ceramics</router-link>
      <router-link to="/about">Cutlery</router-link>
    </nav>

    <FirstBlock />


    <!-- <router-view/> -->
  </div>
</template>
<script>
import FirstBlock from './components/FirstBlock.vue';
import HeaderTop from './components/HeaderTop.vue';


export default {
  name: "App",
  components: {
    HeaderTop,
    FirstBlock
  }
}
</script>
<style>

.main-container{
  margin: 0 auto;
  width: 1440px;
  font-family: sans-serif;
}

.navi-item{
    margin-right: 44px;
}
.navi-list{
    display: flex;
    justify-content: center;
    padding: 20px 0 20px 0;
}

navi-item a{
    text-decoration: none;
    color: #726E8D;
    font-size: 22px;

}
</style>
