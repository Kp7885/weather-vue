<template>
  <div>
    <nav class="navbar">
      <h2 class="logo">WeatherVue</h2>
      <div class="menu">
        <router-link to="/">Home</router-link>
        <router-link to="/dashboard">Dashboard</router-link>
        <router-link to="/about">About</router-link>
      </div>
    </nav>
    <router-view />
  </div>
</template>

<style scoped>
.navbar {
  background: #1e293b;
  color: white;
  padding: 12px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  margin: 0;
}
.menu a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
  font-weight: bold;
}
.menu a:hover {
  color: #38bdf8;
}
</style>
