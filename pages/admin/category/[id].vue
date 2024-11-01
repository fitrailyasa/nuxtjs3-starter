<!-- pages/admin/category/_id.vue -->
<template>
  <div>
    <h1>Category: {{ $route.params.id }}</h1>
    <!-- Category-specific logic here -->
  </div>
</template>

<script setup>
  definePageMeta({
  layout: 'admin' // Layout admin
  });
</script>