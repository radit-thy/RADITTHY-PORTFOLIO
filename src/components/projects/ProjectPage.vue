<template>
  <div class="container">
    <div
      class="profile-right d-flex flex-column align-items-center justify-content-center"
    >
      <div id="profile-stats">
        <h2 class="skills">My Projects</h2>
      </div>
    </div>
    <!-- Main project -->
    <div
      class="projects d-flex flex-wrap align-items-center justify-content-center"
    >
    <!-- Project 1 -->
      <div class="main-card d-flex">
        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
        <div class="projectDetails">
          <h1 class="title">Pont Of Sales (POS) System</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items1"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Project 2 -->
      <div class="main-card d-flex">
        <div class="projectDetails">
          <h1 class="title">Facebook API by using Laravel</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items2"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
      </div>
    <!-- Project 3 -->
      <div class="main-card d-flex">
        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
        <div class="projectDetails">
          <h1 class="title">Leave Management System</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items3"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Project 4 -->
      <div class="main-card d-flex">
        <div class="projectDetails">
          <h1 class="title">Care Finder System</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items4"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
      </div>
    <!-- Project 5 -->
      <div class="main-card d-flex">
        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
        <div class="projectDetails">
          <h1 class="title">Airline Management System</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items5"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Project 6 -->
      <div class="main-card d-flex">
        <div class="projectDetails">
          <h1 class="title">Algorithm Game  Using Python</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items6"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
      </div>
    <!-- Project 7 -->
      <div class="main-card d-flex">
        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
        <div class="projectDetails">
          <h1 class="title">Music Band Website Interface</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items7"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Project 8 -->
      <div class="main-card d-flex">
        <div class="projectDetails">
          <h1 class="title">Software Deployment</h1>
          <p class="desc_1 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <p class="desc_2 mt-3">
            The first project build for static website interface for a music
            band.
          </p>
          <div class="item">
            <span class="fa fa-calendar mr-2"></span>
            January 2022 - Present
          </div>
          <div class="main-cardItem d-flex flex-wrap">
            <div
              class="card card-item"
              style="width: 6em"
              v-for="(item, index) in items8"
              :key="index"
            >
              <img :src="item.logo" class="card-img-top" alt="image" />
              <div class="card-body">
                <!-- <p class="card-text">{{ item.name }}</p> -->
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3" style="max-width: 540px">
          <div class="row g-0">
            <div class="col-md-4">
              <img src="" class="img-fluid rounded-start" alt="image" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProjectPage",
  props: {
    msg: String,
  },
  data() {
    return {
      items1: [
        {
          name: "Javscript",
          logo: require('@/assets/Programming/javascript.png'),
        },
        {
          name: "Html",
          logo: require('@/assets/Programming/html.png'),
        },
        {
          name: "CSS",
          logo: require('@/assets/Programming/css.png'),
        },
      ],
      items2: [
        {
          name: "Laravel",
          logo: require('@/assets/Programming/laravel.png'),
        },
        {
          name: "Postman",
          logo: require('@/assets/Tools/postman.png'),
        },
        {
          name: "Swagger",
          logo: require('@/assets/Tools/swagger.png'),
        },
        {
          name: "Jira",
          logo: require('@/assets/Programming/jira.png'),
        },
      ],
      items3: [
        {
          name: "PHP",
          logo: require('@/assets/Programming/php.png'),
        },
        {
          name: "MySQL",
          logo: require('@/assets/Programming/mysql.png'),
        },
        {
          name: "Bootstrap",
          logo: require('@/assets/Programming/bootstrap.png'),
        },
        {
          name: "Jira",
          logo: require('@/assets/Programming/jira.png'),
        },
        {
          name: "Figma",
          logo: require('@/assets/Programming/figma.png'),
        },
      ],
      items4: [
        {
          name: "Laravel",
          logo: require('@/assets/Programming/laravel.png'),
        },
        {
          name: "Vue",
          logo: require('@/assets/Programming/vuejs.png'),
        },
        {
          name: "Mysql",
          logo: require('@/assets/Programming/mysql.png'),
        },
        {
          name: "Element Plus",
          logo: require('@/assets/Programming/elementplus.png'),
        },
        {
          name: "Jira",
          logo: require('@/assets/Programming/jira.png'),
        },
        {
          name: "Figma",
          logo: require('@/assets/Programming/figma.png'),
        },
      ],
      items5: [
        {
          name: "OOP Concepts",
          logo: require('@/assets/Programming/oopconcepts.png'),
        },
        {
          name: "TypeScript",
          logo: require('@/assets/Programming/typescript.png'),
        },
        {
          name: "Jira",
          logo: require('@/assets/Programming/jira.png'),
        },
      ],
      items6: [
        {
          name: "Python",
          logo: require('@/assets/Programming/python.png'),
        },
        {
          name: "Figma",
          logo: require('@/assets/Programming/figma.png'),
        },
      ],
      items7: [
        {
          name: "HTML",
          logo: require('@/assets/Programming/html.png'),
        },
        {
          name: "CSS",
          logo: require('@/assets/Programming/css.png'),
        },
        {
          name: "SASS",
          logo: require('@/assets/Programming/sass.png'),
        },
        {
          name: "Figma",
          logo: require('@/assets/Programming/figma.png'),
        },
      ],
      items8: [
        {
          name: "WordPress",
          logo: require('@/assets/Tools/wordpress.png'),
        },
        {
          name: "Ubuntu",
          logo: require('@/assets/Tools/ubuntu.png'),
        },
        {
          name: "MobaXterm",
          logo: require('@/assets/Tools/mobaxterm.png'),
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
  margin-top: 200px;
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
  height: 500px;
  width: 600px;
}
.card:hover {
  background: #253349;
  transition: background 0.3s ease;
  cursor: pointer;
  transform: scale(1.01);
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.projects {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
}
.skills {
  color: #00bfff;
}
.main-card {
  width: 1145px;
  gap: 70px;
  margin-top: 120px;
}
.title {
  font-size: 50px;
  font-weight: bold;
  color: #00bfff;
}
.projectDetails {
  color: #ffffff;
  text-align: start;
}
.desc_1,
.desc_2 {
  font-size: 20px;
}
.card-item {
  height: 100px;
  align-items: center;
  gap: 20px;
}
.main-cardItem {
  gap: 15px;
  margin-top: 85px;
}
</style>
