<template>
  <div class="right-section">
      <h1 class="product-title">The Sofa</h1>
      <p class="product-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br/>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      <div class="pay-now-section">
        <div class="pay-now">
          <span class="pay-now-title">Pay Now</span>
          <h2 class="price">$1,250</h2>
          <p><del>$1,450</del></p>
          <p>$200 OFF with code</p> 
        </div>
        <!-- <div class="divider"></div> -->
        <div class="pay-as-low">
          <span class="pay-as-low-title">Pay as low as</span>
          <h2 class="price">$25/month</h2>
          <p class="pay-as-low-title">with Klarna</p>
          <a href="#" class="learn-more">Learn More</a> 
        </div> 
      </div>
      <!-- <button class="checkout-button">Add To Cart</button><br/>
      <a href="#" class="save-design-link">Save Design For Later</a> -->
      <!-- <div class="divider-two"></div> -->

      <!-- <div class="bottom-right-section">
        <h1 class="product-title">1.Choose A Fabric </h1> 
        <p class="pay-now-title">Choose your choice from fabrics to leather </p>
        <span>Fabric Choices</span>

      <div class="bottom-right-sofas">
        <img src="#" alt="amber-sofa" />
        <button type="button">Amber</button>
        <img src="#" alt="charocal-sofa" />
        <button type="button">Charocal</button>
        <img src="#" alt="red-sofa"/>
        <button type="button">Red</button>
      </div>
    </div>  -->
  </div>
</template>

<script>
export default {
  name: 'RightSection'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');
 
 .right-section {
   display:flex;
   flex-direction: column;
   height: auto;
   width: 50%;
   margin-left: 38rem;
   margin-top: 4rem;
 }

 .product-title {
    font-family: 'Bungee', cursive;
    font-size: 40px;
    color: #0547A0;
 }

 .product-description {
    font-size: 16px;
    text-align: left;
 }

 .price {
   color: red;
   font-size: 35px;
 }

 .pay-now-section {
    display: flex;
    justify-content: space-between;
    padding-bottom: 10px;
    width: 100%;
 }

 .pay-now {
    margin-top: 25px;
    margin-left: 150px;
    font-weight: normal;
    font-size: 20px;
 }
 
 .pay-as-low {
    margin-top: 25px;
    margin-right: 200px;
    font-weight: normal;
    font-size: 20px;
 }

 .learn-more {
   text-decoration: none;
   color: #444444;
 }

.checkout-button {
  background: #0D6EF0;
  border-color:#0D6EF0;
  border-radius: 6px;
  font-family: 'Bungee', cursive;
  font-size: 20px;
  width: 350px;
  height: 50px;
  top: 25%;
  color: #FFFFFF;
  line-height: 24px;
  margin-bottom: 28px;
}

.save-design-link {
  font-family: 'Bungee', cursive;
  font-size: 14px;
  line-height: 17px;
  color: #444444;
  align-items: center;
  text-align: center;
  margin-top: 20px;
}

.divider {
  display: block;
  width: 10rem;
  border-top: 2px solid #444444;
  transform: rotate(90deg);
  margin-left: -200px;
}

.divider-two {
  display: block;
  width: 80%;
  border-top: 2px solid #000000;
  margin-left: 100px;
  margin-top: 50px;
}
</style>