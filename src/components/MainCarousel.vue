<template>
  <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <div class="position-relative">
          <div class="position-absolute slide-text">
            <div class="w-50">
              <h1>
                Buy And Sell Your Car At Its Value
              </h1>
              <p>
                Find the right price and dealer.
              </p>
              <button class="btn text-light d-flex  align-items-center gap-3">
                Learn More
                <img src="../img/svg/right-arrow-svgrepo-com.svg" alt="">
              </button>
            </div>
          </div>
          <img src="../img/slider/slider-autocar-5.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
      <div class="carousel-item">
        <div class="position-relative">
          <div class="position-absolute slide-text">
            <div class="w-50">
              <h1>
                Buy And Sell Your Car At Its Value
              </h1>
              <p>
                Find the right price and dealer.
              </p>
              <button class="btn text-light d-flex align-items-center gap-3">
                Learn More
                <img src="../img/svg/right-arrow-svgrepo-com.svg" alt="">
              </button>
            </div>
          </div>
          <img src="../img/slider/slider-autocar-6.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>
<script>

export default {
    name : 'MainCarousel'
}

</script>
<style lang="scss">
    .slide-text
    {
      top: 20%;
      left: 20%;
      color: white;
    }

    h1{
      font-weight: bold;
      font-size: 2.5rem;
    }

    p{
      font-weight: bold;
      font-size: 1.2rem;
    }
</style>