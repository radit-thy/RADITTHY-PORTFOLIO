
<template>
  <div id="bg">
    <NavBar/>
    <!-- <NavView msg="This is Nav Page" /> -->
    <ProfilePage msg="This is Profile Page" />
    <SkillPage msg="This is Skill Page" />
    <ProjectPage msg="This is Project Page" />
    <FooterPage msg="This is Skill Page" />
  </div>
</template>

<script>
import FooterPage from './components/footer/FooterPage.vue';
import NavBar from './components/navbar/NavBar.vue';
import ProfilePage from './components/profile/ProfilePage.vue';
import SkillPage from './components/skills/SkillPage.vue';
import ProjectPage from './components/projects/ProjectPage.vue';
// import NavView from './components/navbar/NavView.vue';



export default {
  name: 'HomeView',
  components: {
    NavBar,
    ProfilePage,
    SkillPage,
    FooterPage,
    ProjectPage,
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* margin-top: 60px; */
  width: 100%;
  /* height: 100vh; */
  background-color: #111729; /* Set the background to black */
  color: white; /* Change text color to white to make it readable on black background */
}


</style>
