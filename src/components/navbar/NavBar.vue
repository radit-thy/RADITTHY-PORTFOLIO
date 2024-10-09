<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <!-- Navbar Brand -->
      <a class="navbar-brand" href="#">RD</a>

      <!-- Toggler/collapsing button for small screens -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="true"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Navbar Items with large spacing between them -->
      <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
        <ul class="navbar-nav custom-nav-spacing">
          <li class="nav-item">
            <a class="nav-link active" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
.custom-nav-spacing {
  /* margin-bottom: 30px;  */
}

.custom-nav-spacing li {
  margin: 0 30px; 
  /* margin-top: 40px; */
}

.navbar-nav .nav-link {
  font-size: 1rem;
  color: #000;
}

.navbar-nav .nav-link:hover {
  color: #0d6efd;
}
</style>
