<script setup lang="ts">
import { RouterView } from "vue-router";
</script>

<template>
  <section>
    <div class="teste">
      <h1>This is an abouts page</h1>
    </div>
  </section>
  <RouterView />
</template>

<style lang="scss">
.teste {
  display: flex;
  justify-content: center;
}
</style>
