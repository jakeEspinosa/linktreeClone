<script lang="ts" setup>
import LinkyProfilePicture from "@/components/LinkyProfilePicture.vue";
</script>

<template>
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
</template>

<style scoped>
.pfp {
  padding-top: 1rem;
}

.main {
  min-height: 75%;
  padding-top: 1rem;
}

.footer {
  height: 10%;
}
</style>