<template>
  <header class="header">
    <div class="header-inner">
      <div class="logo">ProductivityPro</div>
      <nav class="nav">
        <router-link to="/" class="nav-link">Home</router-link>
        <router-link to="/about" class="nav-link">About</router-link>
        <router-link to="/contact" class="nav-link">Contact</router-link>
        <router-link to="/blog" class="nav-link">Blog</router-link>
      </nav>
      <button class="sign-up-btn">Sign up</button>
    </div>
  </header>
</template>

<script setup>
</script>

<style scoped>
.header {
  width: 100%;       /* 全屏 */
  background: #fff;
  padding: 1.2rem 0;
  margin: 0;          /* 无外边距 */
}
.header-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.logo {
  font-size: 1rem;
  font-weight: 700;
  color: #1e293b;
}
.nav {
  display: flex;
  gap: 2rem;
}
.nav-link {
  text-decoration: none;
  color: #475569;
  font-size: 0.85rem;
}
.nav-link:hover {
  color: #2563eb;
}
.sign-up-btn {
  background: #ffffff;
  color: #2563eb;
  border: 1px solid #2563eb;
  padding: 0.5rem 1rem;
  border-radius: 999px;
  font-size: 0.8rem;
  cursor: pointer;
}
</style>