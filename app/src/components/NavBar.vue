<template>
  <div class="navbar-section"> 
      <nav class="navbar">
        <div class="navbar-row"> 
          <div class="navbar-left-side">
            <a href="#" class="navbar-item">The Sofa</a>
            <a href="#" class="navbar-item">Reviews</a>
            <a href="#" class="navbar-item">About Us</a>
          </div>
          <img alt="all day logo" id="logo" src="https://helixsleep-code-challenge.s3.amazonaws.com/logo.png" height="50"><a href="#" alt="all day logo"></a>
          <div class="navbar-right-side">
            <a href="#" class="navbar-item">Showroom</a>
            <a href="#" class="navbar-item">Swatches</a>
          </div>
        </div>
      </nav>
  </div> 
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');

  .navbar-row {
    margin-top: px;
  }

  
  #logo {
    position: relative;
    display: inline-block;
    bottom: 10px;
    margin-right: 50px;
  }

  .navbar-left-side {
    float: left;
    margin-left: 10px;
  }
  .navbar-right-side {
    float: right;
    margin-right: 10px;
  }

  a.navbar-item {
    font-family: 'Bungee',cursive;
    color: #4B4B4B;
    font-size: 16px;
    line-height: 16px;
    width: 84px;
    height: 17px;
    left: 37px;
    top: 47px;
    text-decoration: none;
    list-style-type: none;
    padding: 10px;
  }

</style>
