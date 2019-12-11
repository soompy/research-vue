<template>
  <div id="app">
    <div id="nav">
      <h1>AZShop</h1>
      <div class="link">
         <router-link to="/">Home</router-link> |
         <router-link to="/about">About</router-link>
      </div>
      <a class="basket" href="#"><img src="./assets/basket.png" width="30px" alt="장바구니"> (0)</a>
    </div>
    
    <router-view/>

    <footer id="footer">
      <ul class="row">
        <li class="col-sm-3"><a href="#">홈</a></li>
        <li class="col-sm-3"><a href="#">카테고리</a></li>
        <li class="col-sm-3"><a href="#">검색</a></li>
        <li class="col-sm-3"><a href="#" class="last">마이페이지</a></li>
      </ul>
    </footer>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  display: flex;
  padding: 20px;
  border-bottom: 1px solid #e0e0e0;
}

#nav h1 {
  color: #f4793e;
  font-weight: bold;
  font-size: 25px;
  margin-right: auto;
}

#nav .link {
  margin: auto;
}

#nav a {
  font-weight: blod;
  color: #333;
  font-size: 18px;
  padding: 0 12px;
}

#nav .basket {
  display: block;
  font-size: 14px;
  color: #f4793e;
  font-weight: bold;
  margin-left: auto;
  vertical-align: middle;
}

#nav a.router-link-exact-active {
  color: #f4793e;
}

#footer {
  border-top: 1px solid #e0e0e0;
}

#footer a {
  display: block;
  color: #333;
  padding: 20px 0;
}

#footer a:after {
  position: absolute;
  right: 0;  
  width: 1px;
  height: 10px;
  background: #eee;
  content: "|";
}

#footer .last:after{
  display: none;
}

#footer a:hover {
  color: #f4793e;
}

@media (max-width: 575px) {
  #footer a:after {
    display: none;
  }
}
</style>
