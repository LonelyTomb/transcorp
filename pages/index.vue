<template>
  <div class="home-page p-0">
    <Welcome />
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  components: {
    Welcome: () => import('~/components/Welcome')
  }
}
</script>

<style lang="scss">
.home-page {
}
</style>
