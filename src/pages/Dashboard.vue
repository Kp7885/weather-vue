<template>
  <section class="dashboard-container">
    <h1 class="title">Dashboard ☁️</h1>

    <p class="subtitle">
      Explore weather conditions with modern UI — fast, simple and friendly!
    </p>

    <div class="weather-grid">
      <div class="card">
        <h2>🌤 Current Weather</h2>
        <p>View today’s temperature, conditions, and wind patterns.</p>
      </div>

      <div class="card">
        <h2>📅 Weekly Forecast</h2>
        <p>Plan ahead with a multi-day weather outlook.</p>
      </div>

      <div class="card">
        <h2>✨ Stylish UI</h2>
        <p>Crafted with Vue components + router navigation.</p>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.dashboard-container {
  min-height: 80vh;
  padding: 2rem;
  text-align: center;
  background: #eef9ff;
}

.title {
  font-size: 2.2rem;
  color: #004b80;
}

.subtitle {
  margin-top: 0.5rem;
  font-size: 1.15rem;
  color: #004b80d0;
}

.weather-grid {
  display: grid;
  gap: 1.4rem;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  margin-top: 2rem;
}

.card {
  background: white;
  padding: 1.6rem;
  border-radius: 10px;
  box-shadow: 0 4px 8px #00000015;
  transition: transform 0.2s;
}

.card:hover {
  transform: translateY(-5px);
}
</style>
