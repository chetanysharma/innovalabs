<template>
  <Header/>
  <router-view/>
</template>

<script>
import Header from './components/shared/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>
