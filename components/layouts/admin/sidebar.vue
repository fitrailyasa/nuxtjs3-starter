<template>
  <aside class="sidebar">
    <ul>
      <li><nuxt-link to="/admin/dashboard">Dashboard</nuxt-link></li>
      <li><nuxt-link to="/admin/user">User</nuxt-link></li>
      <li><nuxt-link to="/admin/product">Product</nuxt-link></li>
      <li><nuxt-link to="/admin/category">Category</nuxt-link></li>
      <li><nuxt-link to="/">Logout</nuxt-link></li>
    </ul>
  </aside>
</template>

<script>
export default {}
</script>

<style scoped>
.sidebar {
  width: 250px;
  background-color: #2c3e50;
  color: #ecf0f1;
  padding: 20px;
}

.sidebar ul {
  list-style: none;
  padding: 0;
}

.sidebar li {
  margin: 10px 0;
}

.sidebar li a {
  color: #ecf0f1;
  text-decoration: none;
}

.sidebar li a:hover {
  text-decoration: underline;
}
</style>
