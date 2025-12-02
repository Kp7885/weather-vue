<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary px-3">
      <a class="navbar-brand fw-bold" href="#">🌤 Weather Vue</a>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link to="/" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/dashboard" class="nav-link">Dashboard</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <main class="container mt-4">
      <router-view />
    </main>
  </div>
</template>

<style>
.nav-link.router-link-active {
  background: rgba(255,255,255,0.2);
  border-radius: 6px;
}
</style>
