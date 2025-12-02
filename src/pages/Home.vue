<template>
  <section class="home-container">
    <div class="home-content">
      <h1 class="title">Welcome to WeatherVue 🌤️</h1>

      <p class="description">
        WeatherVue is your friendly weather companion! Explore the atmosphere with a visually
        pleasing interface that introduces you to the project story. This application is built 
        using <strong>Vue.js</strong> to explore modern web frameworks beyond React and deliver 
        a smooth user experience.
      </p>

      <router-link to="/dashboard" class="btn">
        Start Exploring →
      </router-link>
    </div>
  </section>
</template>

<script setup>
// No script needed yet for static content
</script>

<style scoped>
.home-container {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 80vh;
  background: linear-gradient(135deg, #6ec6ff, #9be7ff);
  text-align: center;
  padding: 2rem;
  color: #003b6f;
}

.home-content {
  max-width: 650px;
}

.title {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: 700;
}

.description {
  font-size: 1.15rem;
  margin-bottom: 2rem;
  line-height: 1.6;
}

.btn {
  background: #004b80;
  color: white;
  padding: 0.8rem 1.8rem;
  font-size: 1rem;
  border-radius: 6px;
  text-decoration: none;
  transition: 0.25s ease-in-out;
}

.btn:hover {
  background: #002f4b;
}
</style>
