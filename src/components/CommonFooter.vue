<template>
  <footer>
    <nav class="footer">
      <ul class="flex">
        <li><a href="#">home</a></li>
        <li><a href="#">about</a></li>
        <li><a href="#">service</a></li>
        <li><a href="#">works</a></li>
      </ul>
      <p><small>Copyright 2019 estra inc. All Rights Reserved.</small></p>
    <h3 class="footer-title">estra inc.</h3>
    </nav>
  </footer>  
</template>

<style scoped>
.footer {
  height: 70px;
  background-color: #000;
  position: relative;
}

.footer ul {
  justify-content: flex-end;
}

.footer a {
  color: #fff;
  margin-left: 45px;
  text-decoration: none;
}
.footer p {
  position: absolute;
  bottom: 0;
  left: 590px;
  font-size: 16px;
  padding: 3px;
  color: #fff;
}
@media screen and (max-width: 768px) {
  .footer {
    position: relative;
  }

  .footer p {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    margin: auto;
    text-align: center;
  }
  .footer-title {
    font-size: 25px;
    color: white;
    position: absolute;
    bottom: 40px;
    left: 125px;
  }

  .footer li {
    display: none;
  }
}
</style>