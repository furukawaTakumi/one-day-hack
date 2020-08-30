<template>
  <centering>
    <template #contents>
      <mine-sweeper />
    </template>
  </centering>
</template>

<script>
import Centering from '@/layouts/centering'
import MineSweeper from '@/components/Minesweeper'

export default {
  components: {
    Centering,
    MineSweeper
  }
}
</script>

<style>
</style>
