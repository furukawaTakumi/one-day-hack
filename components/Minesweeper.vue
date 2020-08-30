<template>
<div>
<table id="field" border="1" bordercolor="#333333">
  <tr v-for="row in fieldState" v-bind:key="row.id">
    <td v-for="col in row.line" v-bind:key="col.id"></td>
  </tr>
</table>
<button @click="test">test</button>
</div>
</template>

<script>
export default {
  data () {
    return {
      fieldState: [
        { line: [{ opened: false, bomb: false, id: 0 }, { opened: false, bomb: false, id: 1 }, { opened: false, bomb: false, id: 2 }], id: 0 },
        { line: [{ opened: false, bomb: false, id: 0 }, { opened: false, bomb: false, id: 1 }, { opened: false, bomb: false, id: 2 }], id: 1 },
        { line: [{ opened: false, bomb: false, id: 0 }, { opened: false, bomb: false, id: 1 }, { opened: false, bomb: false, id: 2 }], id: 2 }
      ]
    }
  },
  methods: {
    test () {
      // table = document.getElementById("field");
      // var newElement = document.createElement("th");
      // x = 10;
      // y = 10;
      // for(i = 0;i < y;i++){
      //   for(j = 0;j < x;j++){
      //     table.appendChild(newElement);
      //   }
      // }
    }
  }
}
</script>

<style scoped>
#field {
  width: 400px;
  height: 400px;
}
</style>
