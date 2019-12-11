<template>
  <div class="home">
    <div class="inner">
      <HelloWorld msg="오늘의 추천 상품"/>
      <ul class="list row">
        <li class="col-sm-6 item">
          <div id="product" class="list_view">
            <figure class="thumb">
              <div class="product">
                <img src="../assets/cup.png" alt="cup" width="250px">       
              </div>
            </figure>
            <div class="info">
              <div class="name"> YETI Rambler 14 oz Stainless Steel Vacuum Insulated Mug with Lid</div>
              <div class="price">$25</div>
              <div class="type">
                <p class="color">color</p>
                <span id="gray" class="gray">gray</span>
                <span id="red" class="red">red</span>
                <span id="purple" class="purple">purple</span>
              </div>
              <button class="cart_btn">Add to Cart</button>
            </div>
          </div>
        </li>
        <li class="col-sm-6 item">
          <div id="product" class="list_view">
            <figure class="thumb">
              <div class="product">
                <img src="../assets/watch.png" alt="watch" width="250px">       
              </div>
            </figure>
            <div class="info">
              <div class="name"> VATI Sport Band Compatible for Apple Watch Band 38mm 40mm 42mm 44mm</div>
              <div class="price">$5.00 - $35.99</div>
              <div class="type">
                <p class="color">color</p>
                <span id="pink" class="pink">pink</span>
                <span id="yellow" class="yellow">yellow</span>
                <span id="green" class="green">green</span>
              </div>
              <button class="cart_btn">Add to Cart</button>
            </div>
          </div>
        </li>
        <li class="col-sm-6 item">
          <div id="product" class="list_view">
            <figure class="thumb">
              <div class="product">
                <img src="../assets/controller.png" alt="controller" width="250px">       
              </div>
            </figure>
            <div class="info">
              <div class="name"> DualShock 4 Wireless Controller for PlayStation 4</div>
              <div class="price">$46</div>
              <div class="type">
                <p class="color">color</p>
                <span id="gold" class="gold">gold</span>
                <span id="blue" class="blue">blue</span>
                <span id="white" class="white">white</span>
              </div>
              <button class="cart_btn">Add to Cart</button>
            </div>
          </div>
        </li>
        <li class="col-sm-6 item">
          <div id="product" class="list_view">
            <figure class="thumb">
              <div class="product">
                <img src="../assets/illy.png" alt="illy" width="250px">       
              </div>
            </figure>
            <div class="info">
              <div class="name"> Illy 60296 y3.2 Espresso and Coffee Machine</div>
              <div class="price">$99</div>
              <div class="type">
                <p class="color">color</p>
                <span id="origin" class="origin">origin</span>
                <span id="skyblue" class="skyblue">skyblue</span>
                <span id="black" class="black">black</span>
              </div>
              <button class="cart_btn">Add to Cart</button>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>


<style>
  .row {
    padding: 0;
    margin: 0;
  }

  li {
    list-style: none;
  }

  .inner {
    max-width: 1200px;
    margin: auto; 
  }

  .list .list_view {
    display: block;
    color: #333;
    border: 1px solid #ccc;
  }

  .item {
    margin-bottom: 30px;
  }

  .info {
    padding: 10px 10px 20px;
  }

  .price {
    margin: 15px 0;
  }

  .type {
    display: flex;    
  }

  .type .color {
    font-weight: bold;
    margin-right: 15px;
  }

  .type span {
    width: 30px;
    height: 30px;
    border: 1px solid #eeeeee;
    box-shadow: 1px 1px 1px 2px #eee;
    margin: 0 6px 0 0;
    border-radius: 50%;
    text-indent: -9999px;
    overflow: hidden;
  }

  .cart_btn {
    margin-top: 20px;
    padding: 8px 10px;
    border: 1px solid #f4793e;
    background: #fff;
    color: #f4793e;
    font-weight: bold;
    -webkit-transition-duration: 0.4s;
    transition-duration: 0.4s;
  }

  .cart_btn:hover {
    background: #f4793e;
    color: #fff;
  }

  .gray {
    background: #333;
  }

  .red {
    background: red;
  }

  .purple {
    background: purple;
  }

  .pink {
    background: pink;
  }

  .yellow {
    background: yellow;
  }

  .green {
    background: green;
  }

  .gold {
    background: gold;
  }

  .blue {
    background: blue;
  }

  .white {
    background: white;
  }

  .origin {
    background: #bc001a;
  }

  .skyblue {
    background: skyblue;
  }

  .black {
    background: black;
  }


</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}


</script>
