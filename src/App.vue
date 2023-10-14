<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
  <header class="header">
    <LinkyProfilePicture image-url="src/assets/images/Espinosa.jpg"/>
    <h1>Full stack software engineer passionate about learning</h1>
</header>
  <main class="main">
    <a href="https://www.jakeespinosa.com/blog" target="_blank">
      <button>
        Blog
      </button>
    </a>
    <a href="https://github.com/jakeEspinosa" target="_blank">
      <button>
        GitHub
      </button>
    </a>
    <a href="https://www.linkedin.com/in/jake-espinosa/" target="_blank">
      <button>
        LinkedIn
      </button>
    </a>
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
  gap: 1.5rem;
}

.footer {
  height: 10dvh;
}
h1, h2 {
  width: 40ch;
  text-align: center;
  font-style: italic;
  color: #f5e9e2;
}

button {
  color: #0b0014;
  background-color: #f5e9e2;
  width: 40ch;
  border-radius: 10px;
  height: 10ch;
}

button:hover {
  transform:scale(1.1,1.1);
}
</style>
