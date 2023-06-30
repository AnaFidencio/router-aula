<script setup></script>

<template>
  
  <main>
    <router-view/>
  </main>
  
  <aside>
    <nav class="menu">
      <router-link to="/" class="home" >Home</router-link>
      <router-link to="/about" class="about">About</router-link> 
    </nav>
  </aside>
  <footer>FOOTER</footer>
</template>

<style scoped>
.menu{ 
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
</style>
