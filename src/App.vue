<template>
<router-view></router-view>
</template>

<script>
import { mapState } from 'vuex'
export default {
  name: 'App',
  components: {
  },
  computed: {
    ...mapState(['user'])
  }
}
</script>

<style>
</style>
