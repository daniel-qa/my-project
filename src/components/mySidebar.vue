<template>
  <aside class="sidebar">
    <h2>側邊欄</h2>
    <ul>
      <li><router-link to="/">首頁</router-link></li>
      <li><router-link to="/about">關於我們</router-link></li>
      <li><router-link to="/contact">聯繫我們</router-link></li>
    </ul>
  </aside>
</template>

<style scoped>
.sidebar {
  width: 250px;
  background-color: #f4f4f4;
  padding: 20px;
  box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
}
</style>
