<template>
  <div class="container">hhhhhhhhh</div>
</template>

<script lang="ts">
import { reName } from '@/utils/utils.ts'
export default {
  name: 'ChatWs',
  data () {
    return {
      list: [],
    }
  },
  methods: {
    getRename () {
      const name = reName('zhout')
      console.log(name)
    }
  }
}
</script>

<style></style>
