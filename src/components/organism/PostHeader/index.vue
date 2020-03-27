<template>
  <header>
    <div class="navBar">
      <div class="logo">
        <a href="#"><img src="@/images/main_logo.png" height="100%"/></a>
      </div>
      <div class="menu">
        <ul>
          <li><p>메뉴1</p></li>
          <li><p>메뉴2</p></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  /* background: yellow; */
  padding-left: 100px;
  padding-right: 100px;
  border-bottom: 0.5px solid #eee;
}

.navBar {
  /* background: blue; */
  height: 70px;
}

.navBar::after {
  content: '';
  display: block;
  clear: both;
}

.logo {
  height: 100%;
  float: left;
}

.menu {
  height: 100%;
  float: left;
}

ul {
  color: #444;
  list-style: none;
  margin: 0;
  padding: 0;
  height: 100%;
}

ul::after {
  content: '';
  display: block;
  clear: both;
}

li {
  height: 100%;
  padding-left: 30px;
  padding-right: 30px;
  line-height: 100%;
  float: left;
  cursor: pointer;
}

li p {
  padding: 0;
  margin: 0;
  top: 50%;
  position: relative;
  transform: translateY(-50%);
}

@media (max-width: 1024px) {
  header {
    padding: 0;
  }
}
</style>
