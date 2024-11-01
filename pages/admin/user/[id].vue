<!-- pages/admin/user/_id.vue -->
<template>
  <div>
    <h1>User: {{ $route.params.id }}</h1>
    <!-- User-specific logic here -->
  </div>
</template>

<script setup>
  definePageMeta({
  layout: 'admin' // Layout admin
  });
</script>