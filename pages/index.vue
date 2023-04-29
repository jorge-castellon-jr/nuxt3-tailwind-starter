<template>
  <div class="p-4">
    <h1 class="text-3xl">Components</h1>
    <div class="section">
      <h2 class="text-2xl">BaseAutocomplete</h2>
      <BaseAutocomplete />
    </div>
    <div class="section">
      <h2 class="text-2xl">BaseButton</h2>
      <p>Props: type, color, rounded, variant, block, to, href, size, shadow</p>
      <BaseButton>Base Button</BaseButton>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.section {
  margin-top: 2rem;
}
</style>
