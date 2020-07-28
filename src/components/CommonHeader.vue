<template>
  <header>
    <div class="flex between">
      <h1>estra inc.</h1>
      <nav class="header-nav">
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </nav>
    </div>
    <div id="humbrger">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </header>
</template>

<style scoped>
header {
  height: 70px;
  background: #000;
}

header > div h1 {
  color: #fff;
  line-height: 70px;
  margin-left: 30px;
}
.header-nav li {
  display: inline-block;
  margin-right: 40px;
}

.header-nav a {
  font-size: 13px;
  text-decoration: none;
  color: #fff;
}
@media screen and (max-width: 768px) {
  #humbrger {
    width: 40px;
    height: 40px;
    position: absolute;
    top: 15px;
    right: 20px;
    cursor: pointer;
    transition: 0.4s;
  }

  #humbrger span {
    width: 35px;
    height: 3px;
    position: absolute;
    left: 2px;
    background-color: white;
    transition: 0.8s;
  }

  #humbrger span:nth-of-type(1) {
    top: 10px;
  }
  #humbrger span:nth-of-type(2) {
     top: 20px;
  }
  #humbrger span:nth-of-type(3) {
   top: 30px;
  }

  .header-nav {
    display: none;
  }
}
</style>