<template>
    <h3>{{ msg }}</h3>
    <div class="container d-flex flex-wrap">
      <div class="profile-right d-flex flex-column align-items-center justify-content-center">
        <div id="profile-stats">
          <h2>Stats</h2>
        </div>
      </div>
      <div class="profile-left d-flex flex-column align-items-center justify-content-center">
        <div id="profile-info">
          <h1>{{ msg }}</h1>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "NavView",
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
    align-items: center;
    background: #adaaaa;
    width: 1145px;
    flex-wrap: wrap;
  }
  
  .profile-left, .profile-right {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
  }
  
  .profile-left {
    background: #646363;
    padding: 20px;
  }
  
  .profile-right {
    background: #ad5c5c;
    padding: 20px;
  }
  
  </style>
  