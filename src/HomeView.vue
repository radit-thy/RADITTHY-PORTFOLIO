<template>
  <NavBar msg="Welcome to Your Vue.js App"/>
  <ProfilePage msg="Welcome to Your Vue.js App"/>
  <FooterPage msg="Welcome to Your Vue.js App"/>
  
</template>
<script>
import FooterPage from './components/FooterPage.vue';
import NavBar from './components/NavBar.vue'
import ProfilePage from './components/ProfilePage.vue'


export default {
  name: 'HomeView',
  components: {
    NavBar,
    ProfilePage,
    FooterPage
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>