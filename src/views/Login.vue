<template>

</template>

<script>
import { GetUser } from '@/store/user'
export default {
  name: 'User.vue',
  methods: {
    getUser () {
      return GetUser
    }
  }
}
</script>

<style scoped>

</style>
