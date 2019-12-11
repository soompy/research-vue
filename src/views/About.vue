<template>
  <div class="about">
    <div class="inner">
      <h1>세상에서 가장 핫한 쇼핑몰</h1>

      <ul class="content">
        <li>
          <h4>"Over 40% of our profits come from selling on AZShop."</h4>
          <h5>Fernando Aguerevere <br>CEO and Partner, Hot Chocolate Design</h5>
          <button class="selling">Start Selling</button>
        </li>
        <li>
          <h4>Start selling on AZShop today</h4>
          <ul class="row description">
            <li class="col-sm-4">
              <p>Reach hundreds of millions of customers</p>
              <span>Access a massive audience of confident customers—in the U.S. alone, Amazon has over 150 million monthly unique visitors.¹ Benefit from a brand that ranks #1 in reputation as determined by a 2018 Nielsen Company survey.²</span>
            </li>
            <li class="col-sm-4">
              <p>Let us do the heavy lifting</p>
              <span>Scale swiftly and reach even more customers with Fulfillment by Amazon, our world-class fulfillment service. We pick, pack, and ship your products and take care of customer service and returns—all so you can focus on growing your business.</span>
            </li>
            <li class="col-sm-4">
              <p>Get your products seen by more shoppers</p>
              <span>Increase your reach and drive sales by advertising your products on Amazon. Keyword-targeted ads appear in high-visibility placements, right where customers will see them, and you only pay when your ad is clicked.</span>
            </li>
          </ul>
        </li>
        <li>
          <h4>Start selling today</h4>
          <h5>Put your products in front of the millions of customers that search Amazon.com every day.</h5>
          <button class="selling">Start Selling</button>
        </li>
      </ul>

    </div>
    
  </div>
</template>

<style>
.inner {
  max-width: 1200px;
}

.about h1 {
  font-size: 20px;
  padding: 40px 0 20px;
  font-weight: bold;
}

.content {
  padding: 0;
}

.content li {
  padding: 30% 0 20%;
  height: 100vh;
}

.content h4{
  font-size: 35px;
  padding: 40px 0 20px;
  font-weight: bold;
}

.content h5 {
  line-height: 30px;
}

.description li {
  padding: 40px 0 20px;
}

.description p {
  font-weight: bold;
  font-size: 20px;
}

.content button {
  margin: 60px 0 20px;
  padding: 10px 20px;
  background: #f4793e;
  color: #fff;
  font-weight: bold;
  border: 1px solid #f4793e;
}

.content button:hover {
  box-shadow: 1px 2px 1px #999;
  text-shadow: 1px 1px 1px #ccc;
}

@media (max-width: 575px) {
  .description li {
    height: 20vh;
  }
}
</style>

<script>


</script>
