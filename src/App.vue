<template>
  <div id="app">
    <Sidebar />
    <main class="content">
      <router-view />
    </main>
  </div>
</template>

<script>
import Sidebar from './components/mySidebar.vue';

export default {
  components: {
    Sidebar,
  },
};
</script>

<style>
#app {
  display: flex;
}

.content {
  flex: 1;
  padding: 20px;
}
</style>
