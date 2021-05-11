<template>
<div id="carouselTestimonials" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselTestimonials" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselTestimonials" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselTestimonials" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="../assets/images/slide.png" class="d-block w-100" alt="...">
      <div class="carousel-caption testimonials__slide d-none d-md-block">
        <h5>First slide label</h5>
        <p>Liber tempor cum soluta eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum, typin no habent claritatem insitam legentis qui facit eorum claritatem. </p>
      </div>
    </div>

    <div class="carousel-item" data-bs-interval="10000">
      <img src="../assets/images/slide.png" class="d-block w-100" alt="...">
      <div class="carousel-caption testimonials__slide d-none d-md-block">
        <h5>First slide label</h5>
        <p>Liber tempor cum soluta eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum, typin no habent claritatem insitam legentis qui facit eorum claritatem. </p>
      </div>
    </div>

    <div class="carousel-item" data-bs-interval="10000">
      <img src="../assets/images/slide.png" class="d-block w-100" alt="...">
      <div class="carousel-caption testimonials__slide d-none d-md-block">
        <h5>First slide label</h5>
        <p>Liber tempor cum soluta eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum, typin no habent claritatem insitam legentis qui facit eorum claritatem. </p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselTestimonials" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselTestimonials" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</template>

<style lang="scss">
	.home {
		&__carousel-indicators {
			bottom: 200px;
		}
	}
</style>
