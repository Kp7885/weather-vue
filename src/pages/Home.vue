<template>
  <section class="page">
    <h1>Welcome to WeatherVue</h1>
    <p>Your simple weather storytelling experience built with Vue!</p>
    <router-link class="btn" to="/dashboard">Go to Dashboard</router-link>
  </section>
</template>

<style scoped>
.page {
  text-align: center;
  padding: 80px;
}
.btn {
  background: #38bdf8;
  padding: 12px 20px;
  border-radius: 6px;
  color: white;
  text-decoration: none;
  margin-top: 20px;
  display: inline-block;
}
.btn:hover {
  background: #0ea5e9;
}
</style>
