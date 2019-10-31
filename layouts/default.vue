<template>
  <div class="page">
    <Header />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'MainLayout',
  components: {
    Header: () => import('~/components/TheHeader'),
    Footer: () => import('~/components/TheFooter')
  }
}
</script>
<style lang="scss">
.page {
}
</style>
