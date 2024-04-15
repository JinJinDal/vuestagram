<template>
  <div class="about">
    <AboutWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>

import AboutWorld from '@/components/AboutWorld.vue'

  export default {
  name: 'AboutView',
  components: {
    AboutWorld
  }
}
</script>