<template>
  <div class="right-section">
      <h1 class="product-title">The Sofa</h1>
      <p class="product-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br/>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      <div class="pay-now-section">
        <div class="pay-now-block">
          <p class="pay-now-title">Pay Now</p>
          <h2 class="price">$1,250</h2>
          <p><del>$1,450</del></p>
          <p>$200 OFF with code</p> 
        </div>
        <div class="divider"></div>
        <div class="pay-now-block">
          <p class="pay-now-title">Pay as low as</p>
          <h2 class="price">$25/month</h2>
          <p>with Klarna</p>
          <a href="#" class="learn-more">Learn More</a> 
        </div> 
      </div>

      <button class="checkout-button">Add To Cart</button><br/>
      <a href="#" class="save-design-link">Save Design For Later</a>
      <div class="divider-two"></div>

      <div class="bottom-right-section">
        <h5 class="bottom-right-title">1.Choose A Fabric </h5> 
        <p class="bottom-right-subtitle">Choose your choice from fabrics to leather</p>
        <h5 class="bottom-right-subtitle">Fabric Choices</h5>
      </div> 

      <div class="bottom-right-sofas">
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/sofa-amber.jpg" alt="amber-sofa" class="sofa" />
        <button type="button" class="bottom-right-button" v-on:click="this.amberOnChange">Amber</button>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/sofa-charcoal.jpg" alt="charocal-sofa" class="sofa"/>
        <button type="button" class="bottom-right-button" v-on:click="this.charocalOnChange">Charocal</button>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/sofa-red.jpg" alt="red-sofa" class="sofa"/>
        <button type="button" class="bottom-right-button" v-on:click="this.redOnChange">Red</button>
      </div>
  </div>
</template>

<script>
export default {
  name: 'RightSection',
  data () {
    return {
      images: [
        'https://helixsleep-code-challenge.s3.amazonaws.com/sofa-amber.jpg',
        'https://helixsleep-code-challenge.s3.amazonaws.com/sofa-charcoal.jpg', 
        'https://helixsleep-code-challenge.s3.amazonaws.com/sofa-red.jpg'
      ]
    }
  }, 
  methods: {
    amberOnChange () {
      this.props.defaultPhoto = this.images[0]
      // console.log('Hello')
    },
    charocalOnChange () {
      // this.props.img = this.images[1]
      console.log('Helloooo')
    }, 
    redOnChange () {
      // this.props.img = this.images[2]
      console.log('Helloooooooo')
    }
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');
 .right-section {
   display:flex;
   flex-direction: column;
   height: auto;
   width: 100;
   margin-left: 50rem;
   margin-top: 3rem;
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

  .pay-now-block {
    margin-left: 70px;
    margin-right: 70px;
  }
  
 .pay-now {
    font-weight: normal;
    font-size: 20px;
 }
 
 .pay-as-low {
    font-weight: normal;
    font-size: 20px;
 }

 .learn-more {
   text-decoration: none;
   color: #444444;
 }

.checkout-button {
  background: #0D6EF0;
  border-radius: 6px;
  border: none;
  font-family: 'Bungee', cursive;
  font-size: 20px;
  width: 375px;
  height: 50px;
  top: 25%;
  color: #FFFFFF;
  line-height: 24px;
  margin-bottom: 28px;
  margin-left: 100px;
}

.save-design-link {
  font-family: 'Bungee', cursive;
  font-size: 14px;
  line-height: 17px;
  color: #444444;
  align-items: center;
  text-align: center;
  padding-bottom: 50px;
  margin-top: -20px;
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
  margin-left: 50px;
  padding-top: 10px;
}

.bottom-right-title {
  font-family: 'Bungee', cursive;
  font-size: 15px;
  color: #0547A0;
  text-align: left;
  padding-left: 50px;
}

.bottom-right-subtitle {
  text-align: left;
  padding-left: 50px;
  margin-top: 30px;
}

.bottom-right-sofas {
  display: flex; 
  flex-direction: row;
  margin-left: 40px;
}

.sofa {
  height: 90px;
  width: 134px;
  padding-left: 10px;

}

.bottom-right-button {
  width: 133px;
  height: 40px;
  background: #E8E8E8;
  border-radius: 6px;
  border: none;
  margin-top: 120px;
  margin-left: -130px;
}
</style>