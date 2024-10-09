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
        <img :src="item.logo" class="card-img-top" alt="image" />
        <div class="card-body">
          <p class="card-text">{{ item.name }}</p>
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
          name: "HTML",
          logo: "logo.png",
        },
        {
          name: "CSS",
          logo: "logo.png",
        },
        {
          name: "JavaScript",
          logo: "logo.png",
        },
        {
          name: "PHP",
          logo: "logo.png",
        },
        {
          name: "MYSQL",
          logo: "logo.png",
        },
        {
          name: "Laravel",
          logo: "logo.png",
        },
        {
          name: "Vue",
          logo: "logo.png",
        },
        {
          name: "Node",
          logo: "logo.png",
        },
        {
          name: "Python",
          logo: "logo.png",
        },
        {
          name: "Bootstrap",
          logo: "logo.png",
        },
        {
          name: "Git",
          logo: "logo.png",
        },
        {
          name: "Gira",
          logo: "logo.png",
        },
        {
          name: "Clockify",
          logo: "logo.png",
        },
        {
          name: "Typescript",
          logo: "logo.png",
        },
        {
          name: "Figma",
          logo: "logo.png",
        },
        {
          name: "Git Source",
          logo: "logo.png",
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
  background: #1e293c;
  color: #ffffff;
  height: 250px;
  width: 250px;
  gap: 150px;
}
.card:hover {
  background: #253349;
  transition: background 0.3s ease;
  cursor: pointer;
  transform: scale(1.01);
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border-radius: 15px;
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
</style>
