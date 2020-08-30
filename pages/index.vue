<template>
<<<<<<< HEAD
  <h1 class="red">Hello </h1>
</template>

<script>
  export default {
    asyncData (context) {
      // コンポーネントをロードする前に毎回呼び出されます
      // 名前の通り非同期にすることができます
      // また、返されたオブジェクトはデータオブジェクトとマージされます
      return { name: 'World' }
    }
  }
</script>



=======
  <centering>
    <template #contents>
      <div>MineSweeper Component で置き換える</div>
    </template>
  </centering>
</template>

<script>
import Centering from '@/layouts/centering'

export default {
  components: {
    Centering
  },
  data () {
    return {}
  }
}
</script>

<style>
</style>
>>>>>>> issue#3
