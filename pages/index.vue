<template>
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



