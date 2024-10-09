<template>
  <div class="container d-flex flex-wrap">
    <div class="profile-left d-flex flex-column align-items-center">
      <div id="profile-stats">
        <h4 class="hi">Hi,</h4>
        <h1 class="name mt-3">I'm Radit Thy</h1>
        <h3 class="position mt-3">I am Web Developer</h3>
      </div>
    </div>
    <div class="profile-right d-flex flex-column align-items-center justify-content-center">
      <div id="profile-image">
        <img src="/src/assets/logo.png" alt="Profile Image" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProfilePage",
  props: {
    msg: String,
  },
  methods: {
    handleFollow() {
      // Handle follow action
    },
    handleUnfollow() {
      // Handle unfollow action
    }
  }
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  width: 1145px;
  flex-wrap: wrap;
  margin-top: 100px;
}

.profile-left, .profile-right {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 20px; 

}

.profile-left {
  padding: 20px;
  text-align: start;
}

.profile-right {
  background: #ad5c5c;
  padding: 20px;
}

#profile-image img {
  max-width: 100%;
  border-radius: 50%;
}

#profile-info h1 {
  color: white;
  text-align: center;
}

#profile-actions button {
  margin: 5px;
  padding: 10px 15px;
  background-color: #333;
  color: white;
  border: none;
  cursor: pointer;
}

#profile-actions button:hover {
  background-color: #555;
}
.hi {
  font-size: 40px;
  font-weight: bold;
  color: #b4b3b3;
}
.name {
  font-size: 70px;
  font-weight: bold;
  color: #00BFFF;
}
.position{
  font-size: 50px;
  color: #fdfbfb;
}
</style>
