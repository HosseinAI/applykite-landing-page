<template>
  <div class="newsletter">
    <h2 class="section-title">Subscribe to Our Newsletter</h2>
    <p class="newsletter-description">Stay updated with the latest immigration rules, PhD positions, fee changes, and opportunities.</p>
    <form class="newsletter-form">
      <input type="email" placeholder="Enter your email" />
      <button class="subscribe-button">Subscribe</button>
    </form>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.newsletter {
  text-align: center;
  padding: 2rem;
  background-color: #f7f7f7;
}

.section-title {
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.newsletter-description {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.newsletter-form {
  display: flex;
  justify-content: center;
  align-items: center;
}

input[type="email"] {
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
  margin-right: 1rem;
}

.subscribe-button {
  background: #3498db;
  color: #fff;
  padding: 1rem 2rem;
  border: none;
  cursor: pointer;
  border-radius: 5px;
}

.subscribe-button:hover {
  background: #2587c9;
}
</style>
