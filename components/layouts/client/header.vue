<template>
    <nav class="header">
      <div class="header__title">Landing Page</div>
      <NuxtLink class="nav-link" to="/">
        Home
      </NuxtLink>
      <NuxtLink class="nav-link" to="/about">
        About
      </NuxtLink>
      <NuxtLink class="nav-link" to="/contact">
        Contact
      </NuxtLink>
      <NuxtLink class="nav-link" to="/auth/login">
        login
      </NuxtLink>
      <NuxtLink class="nav-link" to="/auth/register">
        Register
      </NuxtLink>
    </nav>
  </template>
  
  <script>
  export default {}
  </script>
  
  <style scoped>
  .header {
    background-color: #34495e;
    color: #ecf0f1;
    padding: 10px 20px;
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .nav-link {
    color: #ecf0f1;
    text-decoration: none;
  }
  
  .header__title {
    font-size: 20px;
  }
  </style>
  