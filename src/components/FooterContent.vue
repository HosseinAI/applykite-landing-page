<template>
  <footer class="footer">
    <div class="footer-content">
      <p class="footer-text">&copy; 2023 Apply Kite</p>
      <div class="social-links">
        <a href="https://twitter.com/yourtwitter" target="_blank" class="social-link">Twitter</a>
        <a href="https://facebook.com/yourfacebook" target="_blank" class="social-link">Facebook</a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
}
</script>

<style scoped>
.footer {
  background: linear-gradient(135deg,  #000428, #004e92);
  color: #fff;
  text-align: center;
  padding: 2rem 0;
}

.footer-content {
  max-width: 800px;
  margin: 0 auto;
}

.footer-text {
  font-size: 1.2rem;
  margin-bottom: 1rem;
}

.social-links {
  display: flex;
  justify-content: center;
}

.social-link {
  text-decoration: none;
  color: #fff;
  margin: 0 1rem;
  font-size: 1.2rem;
  transition: color 0.3s ease;
}

.social-link:hover {
  color: #3498db;
}

/* This style creates a gradient background that blends blue and red */
</style>

