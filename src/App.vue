<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link :to="{ name: 'login' }" class="navbar-brand"
      >Laravel Passport Vue</router-link
    >
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <router-link :to="{ name: 'register' }" class="nav-link" href=""
            >Register</router-link
          >
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'login' }" class="nav-link" href="#"
            >Login</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
  <router-view />
</template>

<script>
export default {};
</script>

<style>
body {
  background: lightgray !important;
}
</style>
