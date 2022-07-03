<template>
  <nav class="navbar navbar-expand-lg shadow-sm sticky-top bg-white">
    <div class="container">
      <NuxtLink to="/" class="navbar-brand" href="#">Nuxtstrap</NuxtLink>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse d-d-md-flex justify-content-between" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <NuxtLink to="/dashboard" class="nav-link active" aria-current="page">Dashboard</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink to="/about" class="nav-link">About</NuxtLink>
          </li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item">
            <NuxtLink to="/login" class="nav-link">Login</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
</style>