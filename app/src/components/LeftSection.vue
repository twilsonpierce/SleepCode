<template>
    <div class="left-section">
      <div class="left-section-subtitles">
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/padlock.png" alt="padlock" class="padlock-logo"/>
        <p class="main-title">Secure Checkout</p>
        <p class="main-title">Ships in 5-7 Business Days</p> 
      </div>
      <img src="https://helixsleep-code-challenge.s3.amazonaws.com/sofa-red.jpg" alt="red sofa" id="main-product"/>
      <div class="left-section-perks">
        <img src=" https://helixsleep-code-challenge.s3.amazonaws.com/free-shipping.png" alt="free-shipping" class="perk-items"/>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/trial.png" alt="365 day trial" class="perk-items"/>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/made-in-america.png" alt="made in america" class="perk-items"/>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/warranty.png" alt="10 year warranty" class="perk-items"/>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/assembly.png" alt="super easy assembly" class="perk-items"/>
        <img src="https://helixsleep-code-challenge.s3.amazonaws.com/materials.png" alt="high quality materials" class="perk-items"/>
      </div> 
    </div> 
</template>

<script>
export default {
  name: 'LeftSection'
}
</script>

<style scoped>
  .left-section {
    position: absolute;
    left: 0;
    margin-top: 40px;
  }

  .left-section-subtitles{
    display: flex;
    justify-content: space-between;
  }

  .padlock-logo {
    height: 20px; 
    margin-top: 20px;
    margin-left: 20px;
  }
  .main-title {
    display: flex;
    justify-content: space-between;
    padding-right: 15rem;
    padding-top: 5px;
  }

  #main-product {
    width: auto;
    height: 400px;
    margin-left: -225px;
  }
  .left-section-perks {
    margin-right: 230px;
  }
  .perk-items {
    margin-top: 10px;
    padding-left: 30px;
    height: 40px;
  }
</style>