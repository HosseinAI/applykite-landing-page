<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './components/HeaderContent.vue'
import Main from './components/MainContent.vue'
import Footer from './components/FooterContent.vue'

export default {
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
/* Reset some default styles for consistency */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f7f7f7;
  margin: 0;
}

/* Global header style */
.header {
  text-align: center;
  padding: 2rem;
  background-color: #3498db;
  color: white;
}

.header h1 {
  font-size: 2rem;
}

/* Global button style */
button {
  background-color: #3498db;
  color: white;
  padding: 1rem 2rem;
  border: none;
  cursor: pointer;
}

/* Main content section style */
.main {
  margin: 0 auto;
  padding: 2rem;
  background-color: white;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.main h2 {
  font-size: 1.5rem;
}

/* Footer style */
.footer {
  text-align: center;
  padding: 1rem;
  background-color: #3498db;
  color: white;
}
</style>

