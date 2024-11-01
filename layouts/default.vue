<template>
    <div class="client-layout">
      <Header />
      <div class="client-layout__content">
        <div class="client-layout__main">
          <!-- Area untuk konten halaman -->
          <NuxtPage />
        </div>
      </div>
      <Footer />
    </div>
  </template>
  
  <script>
  import Header from '~/components/layouts/client/header.vue'
  import Footer from '~/components/layouts/client/footer.vue'
  
  export default {
    components: {
      Header,
      Footer
    }
  }
  </script>
  
  <style scoped>
  .client-layout {
    display: flex;
    flex-direction: column;
    height: 100vh;
  }
  
  .client-layout__content {
    display: flex;
    flex: 1;
  }
  
  .client-layout__main {
    flex: 1;
    padding: 20px;
    overflow-y: auto;
  }
  </style>
  