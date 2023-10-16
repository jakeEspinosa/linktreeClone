<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
import LinkyButtonLink from "@/components/LinkyButtonLink.vue";
</script>

<template>
  <header class="header">
    <LinkyProfilePicture image-url="src/assets/images/Espinosa.jpg" :alt-text="'Profile picture'" />
    <h1>Full stack software engineer passionate about accesibility</h1>
</header>
  <main class="main">
    <LinkyButtonLink :label="'Blog'" :link="'https://www.jakeespinosa.com/blog'" />
    <LinkyButtonLink :label="'GitHub'" :link="'https://github.com/jakeEspinosa'" />
    <LinkyButtonLink :label="'LinkedIn'" :link="'https://www.linkedin.com/in/jake-espinosa/'" />
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
  min-height: 35dvh;
  justify-content: center;
  gap: 1rem;
}

.main {
  min-height: 55dvh;
  gap: 1.5rem;
}

.footer {
  height: 10dvh;
}
h1, h2 {
  text-align: center;
  font-style: italic;
  color: #f5e9e2;
  word-wrap: break-word;
}
</style>
