<template>
  <div class="container">
    <div
      class="profile-right d-flex flex-column align-items-center justify-content-center"
    >
      <div id="profile-stats">
        <h2 class="skills">Skills and Tools</h2>
      </div>
    </div>
    <div
      class="profile d-flex flex-wrap align-items-center justify-content-center"
    >
      <div class="card" style="width: 15rem" v-for="(item, index) in items" :key="index">
        <div class="card-body">
          <img :src="item.logo" class="card-img-top logo-image" alt="image" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SkillPage",
  props: {
    msg: String,
  },
  data() {
    return {
      items: [
        {
          name: "Laravel",
          logo: require('@/assets/Programming/laravel.png'),
        },
        {
          name: "Vue js",
          logo: require('@/assets/Programming/vuejs.png'),
        },
        {
          name: "JavaScript",
          logo: require('@/assets/Programming/javascript.png'),
        },
        {
          name: "Nodejs",
          logo: require('@/assets/Programming/node.js.png'),
        },
        {
          name: "PHP",
          logo: require('@/assets/Programming/php.png'),
        },
        {
          name: "MySQL",
          logo: require('@/assets/Programming/mysql.png'),
        },
        {
          name: "Python",
          logo: require('@/assets/Programming/python.png'),
        },
        {
          name: "TypeScript",
          logo: require('@/assets/Programming/typescript.png'),
        },
        {
          name: "Bootstrap",
          logo: require('@/assets/Programming/bootstrap.png'),
        },
        {
          name: "HTML",
          logo: require('@/assets/Programming/html.png'),
        },
        {
          name: "CSS",
          logo: require('@/assets/Programming/css.png'),
        },
        {
          name: "Figma",
          logo: require('@/assets/Programming/figma.png'),
        },
        {
          name: "Jira",
          logo: require('@/assets/Programming/jira.png'),
        },
        {
          name: "Clockify",
          logo: require('@/assets/Programming/clockify.png'),
        },
        {
          name: "GitHub",
          logo: require('@/assets/Programming/github.png'),
        },
        {
          name: "Git Source",
          logo: require('@/assets/Programming/gitsourcecontrol.png'),
        },
      ],
    };
  },
};
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
.container {
  align-items: center;
  width: 1145px;
  flex-wrap: wrap;
  margin-top: 300px;
}

.profile-right {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 20px;
}
.card {
  background: #1E293C;
  color: #ffffff;
  height: 250px;
  width: 250px;
}
.card:hover {
  /* background: #253349; */
  /* transition: background 0.3s ease; */
  cursor: pointer;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border-radius: 20px;
  transition: background 0.3s ease-in-out, color 0.3s ease-in-out;
  /* box-shadow: 0 4px 6px rgba(167, 167, 167, 0.1), 0 2px 4px rgba(255, 255, 255, 0.06); */
  transition: box-shadow 0.3s ease-in-out;
  transition: transform 0.9s ease-in-out;
  transform: translateY(-5px);
  transition: box-shadow 0.3s ease-in-out;
  transition: transform 0.3s ease-in-out;
}
.profile {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
}
.skills {
  color: #00bfff;
}
.card-text {
  font-size: 18px;
  text-align: center;
  margin-bottom: 10px;
  font-weight: 100;
  font-weight: bold;
}
.logo-image {
  background: #000;
  /* width: 230px; */
}
</style>
