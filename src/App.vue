<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
   <div>
    <header>
      <nav>
        <router-link to="/">Home</router-link> |
        <router-link to="/login">Login</router-link> |
        <router-link to="/signup">Sign Up</router-link>
        <h1 class="text-3xl font-bold text-blue-600">Tailwind is working!</h1>
      </nav>
    </header>

    <main>
      <router-view />
    </main>

    <footer>
      <p>&copy; 2025 My Vue SPA</p>
    </footer>
  </div>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
