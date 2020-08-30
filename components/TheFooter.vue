<template>
  <div class="footer">
    <div class="footer-logo">
      sysken hackU vol.3
    </div>
    <div class="urllist">
      <ul>
        <li>Github</li>
        <li>Twitter</li>
        <li>HomePage</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.footer {
  background-color: #2f5167;
  color: #fff;
  height: 120px;
  padding: 40px;
}
.footer-logo {
  font-size: 20px;
  float: left;
}
.urllist {
  float: right;
  flex-direction: column;
}
.urllist li {
  padding-bottom: 5px;
}
</style>
