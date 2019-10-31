<template>
  <div class="home-page p-0">
    <Welcome />
    <About />
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  components: {
    Welcome: () => import('~/components/Welcome'),
    About: () => import('~/components/About')
  }
}
</script>

<style lang="scss">
.home-page {
}
</style>
