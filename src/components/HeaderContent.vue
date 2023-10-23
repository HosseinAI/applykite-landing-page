<template>
  <header class="header">
    <div class="header-content">
      <h1 class="header-title">Welcome to Apply Kite community</h1>
      <p class="header-description">Stay updated with our latest positions and updates.</p>
      <button class="join-button" @click="joinTelegram">Join Now</button>
      <div class="kite-animation">
        <img src="@/assets/logo.png" alt="Flying Kite" class="kite">
      </div>
    </div>
  </header>
</template>

<script>
export default {
  methods: {
    joinTelegram() {
      // Add code to open your Telegram channel link
      window.open('https://t.me/ApplyIR2UK', '_blank')
    }
  }
}
</script>

<style scoped>
.header {
  background: linear-gradient(135deg, #000428, #004e92);
  color: #fff;
  text-align: center;
  padding: 2rem 0;
  position: relative;
}

.header-content {
  max-width: 800px;
  margin: 0 auto;
  position: relative;
  z-index: 2;
}

.header-title {
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

.header-description {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.join-button {
  background: linear-gradient(135deg, #4ca1af , #c4e0e5);
  color: #fff;
  font-size: 1.2rem;
  padding: 1rem 2rem;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  transition: background 0.3s ease;
}

.join-button:hover {
  background: #c0392b;
}

.kite-animation {
  position: absolute;
  top: 0px;
  right: 0;
  animation: kiteFly 10s linear infinite alternate;
}

.kite {
  width: 100px;
}

@keyframes kiteFly {
  0% {
    transform: translate(0, 0);
  }
  100% {
    transform: translate(0, -50px);
  }
}
</style>
