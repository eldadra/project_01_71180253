<template>
        <nav>
          <h4>Daftar Menu</h4>
          <div class="link">
            <router-link to="/makanan">Makanan</router-link> |
            <router-link to="/minuman">Minuman</router-link> |
            <router-link to="/snack">Snack</router-link>
          </div>
        </nav>
        <router-view/>
  </template>
  
  <script>
  export default {
    name: 'NavigationMenu',
  }
  </script>

  <style scoped>
    nav {
        height: 100%;
    }

  </style>
  