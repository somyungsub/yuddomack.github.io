<template>
  <aside>
    <div><b>목차</b></div>
    <div class="wrapInput"><input type="text" /></div>
    <div class="wrapContents">
      <div class="content">· 항목1</div>
      <div class="content">· 항목2</div>
      <div class="content">· 항목3</div>
      <div class="content">ㅤ· 항목3-1</div>
      <div class="content">ㅤ· 항목3-2</div>
      <div class="content">ㅤ· 항목3-3</div>
      <div class="content">· 항목4</div>
      <div class="content">· 항목5</div>
      <div class="content">· 항목6</div>
      <div class="content">ㅤ· 항목6-1</div>
      <div class="content">ㅤㅤ· 항목6-1-1</div>
      <div class="content">ㅤㅤ· 항목6-1-2</div>
      <div class="content">ㅤ· 항목6-2</div>
      <div class="content">· 항목7</div>
      <div class="content">· 항목8</div>
      <div class="content">· 항목9</div>
    </div>
  </aside>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
aside {
  background: white;
  /* cyan; */
  float: left;
  width: 256px;
  padding: 10px;
}

.wrapInput {
  width: 100%;
  padding-top: 10px;
}

input {
  width: 100%;
  margin: -3px;
  font-size: 20px;
  border: 0.5px solid #aaa;
}

.wrapContents {
  width: 100%;
  padding-left: 10px;
  padding-top: 10px;
  font-size: 13px;
}

.content {
  padding-top: 5px;
  padding-bottom: 5px;
}

@media (max-width: 768px) {
  aside {
    height: 100%;
    position: absolute;
  }
}
</style>
