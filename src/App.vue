<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
  <header class="header">
    <LinkyProfilePicture image-url="src/assets/images/Espinosa.jpg"/>
    <h1>Short description</h1>
</header>
  <main class="main">
    <button>buttons</button>
    <button>buttons</button>
    <button>buttons</button>
    <button>buttons</button>
  </main>
  <footer class="footer">
    <h2>footer</h2>
  </footer>
</template>

<style scoped>
.header, .main, .footer {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.header {
  height: 22dvh;
}

.main {
  min-height: 68dvh;
}

.footer {
  height: 10dvh;
}
</style>