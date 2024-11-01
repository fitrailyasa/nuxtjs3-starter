<template>
  <div class="admin-layout">
    <Navbar />
    <div class="admin-layout__content">
      <Sidebar />
      <div class="admin-layout__main">
        <!-- Area untuk konten halaman -->
        <NuxtPage />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Sidebar from '~/components/layouts/admin/sidebar.vue'
import Navbar from '~/components/layouts/admin/navbar.vue'
import Footer from '~/components/layouts/admin/footer.vue'

export default {
  components: {
    Sidebar,
    Navbar,
    Footer
  }
}
</script>

<style scoped>
.admin-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.admin-layout__content {
  display: flex;
  flex: 1;
}

.admin-layout__main {
  flex: 1;
  padding: 20px;
  overflow-y: auto;
}
</style>
