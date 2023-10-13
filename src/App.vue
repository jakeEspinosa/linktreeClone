<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
  <div class="container">
    <div class="pfp">
        <LinkyProfilePicture image-url="src/assets/images/Espinosa.jpg"/>
    </div>
    <main class="main">
      <h1>Short description</h1>
      <button>buttons</button>
      <button>buttons</button>
      <button>buttons</button>
      <button>buttons</button>
    </main>
    <footer class="footer">
      <h2>footer</h2>
    </footer>
  </div>
</template>

<style scoped>
.pfp, .main, .footer, .container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  height: 100%;
  flex-direction: column;
}

.pfp {
  padding-top: 1rem;
  height: 20%;
}

.main {
  min-height: 75%;
  flex-direction: column;
  padding-top: 1rem;
  gap: 1.5rem;
}

.footer {
  height: 10%;
}
</style>