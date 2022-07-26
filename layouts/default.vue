<template>
  <div>
    <Header />
    <div class="m-4">
      <nuxt />
    </div>
  </div>
</template>

<script>
import Header from '../components/templates/Header.vue'

export default {
  components: {
    Header,
  },
}
</script>
