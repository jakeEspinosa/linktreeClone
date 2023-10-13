<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
  <div class="grid">
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
.grid {
  height: 100%;
  display: grid;
  grid-template-areas: "header"
                       "main"
                       "footer";
}

.pfp {
  grid-area: "header";
  padding-top: 1rem;
  height: 90%;
}

.main {
  grid-area: "main";
  min-height: 75%;
  padding-top: 1rem;
}

.footer {
  grid-area: "footer";
  height: 10%;
}
</style>