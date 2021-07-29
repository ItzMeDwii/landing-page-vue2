<template>
<nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <router-link class="navbar-brand" to="/">Navbar</router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link class="nav-link" to="/">
            Home
          </router-link>
        </li>
          <router-link class="nav-link" to="/about">
            About
          </router-link>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar-brand {
    font-weight: 700;
}
.router-link-exact-active {
    font-weight: 700;
}
</style>
