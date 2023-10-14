<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
  <header class="header">
    <LinkyProfilePicture image-url="src/assets/images/Espinosa.jpg"/>
    <h1>Full stack software engineer with a passion for accessibility</h1>
</header>
  <main class="main">
    <button>buttons</button>
    <button>buttons</button>
    <button>buttons</button>
    <button>buttons</button>
  </main>
  <footer class="footer">
    <h2>© 2023 Espinosa Enterprises, LLC. All Rights Reserved.</h2>
  </footer>
</template>

<style scoped>
.header, .main, .footer {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.header {
  height: 30dvh;
  justify-content: center;
  gap: 1rem;
}

.main {
  min-height: 60dvh;
}

.footer {
  height: 10dvh;
}
h1, h2 {
  width: 40ch;
  text-align: center;
  font-style: italic;
  color: white;
}

button {
  color: white;
  background-color: #7E04E9;
  width: 40ch;
  border-radius: 10px;
  height: 10ch;
}

button:hover {
  transform:scale(1.1,1.1);
}
</style>
