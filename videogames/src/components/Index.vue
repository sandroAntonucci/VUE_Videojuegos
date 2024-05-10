<template>
    <div class="main-page">
      <header>
        <h1>Videogames</h1>
      </header>
  
      <!-- Lista de videojuegos con cada componente -->
      <div class="videogame-list">
  
        <!-- Placeholder de futuros videojuegos -->
        <!--
        <Videogame
            v-for="videogame in videogames"
            :key="videogame.id"
            :videogame="videogame"
        />
        -->
  
      </div>
  
      <footer>
        <p>&copy; 2024 YourCompany. All rights reserved.</p>
      </footer>
    </div>
  </template>
  
  <script>
  // import Videogame from './Videogame.vue'
  
  export default {
    name: "MainPage",
    data() {
      return {
        videogames: [
          // Placeholder videogames data
        ]
      };
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .main-page {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #f8f8f8;
  min-height: 100vh; 
}

header {
  background-color: #333; 
  color: #fff;
  padding: 20px;
  width: 100%; 
  margin-top: -10px;
}

footer {
  background-color: #333; /* Background color for the footer */
  color: #fff;
  margin-bottom: -10px;
  padding: 20px;
  width: 100%; /* Ensure footer spans the entire width */
  text-align: center;
  margin-top: auto; /* Push the footer to the bottom of the page */
}

.videogame-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
  </style>