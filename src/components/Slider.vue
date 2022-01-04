<template>
  <div class="container">
    <div class="titlePage">
      <div class="title">SÉRIES</div>
    </div>
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="image1.jpg" class="d-block w-100" alt="image" />
          <div class="carousel-caption d-none d-md-block">
            <h5>
              Impeachment : que vaut la série sur l'affaire Clinton-Lewinsky ?
            </h5>
            <p>
              La saison 3 de l'anthologie "American Crime Story" commence dès ce
              28 octobre sur CANAL+.
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="image2.jpg" class="d-block w-100" alt="image" />
          <div class="carousel-caption d-none d-md-block">
            <h5>L'Amour flou : que vaut la série adaptée du film ?</h5>
            <p>
              Romane Bohringer et Philippe Rebbot poursuivent le récit déjanté
              de leur séparation.
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="image3.jpg" class="d-block w-100" alt="image" />
          <div class="carousel-caption d-none d-md-block">
            <h5>Il n'y a pas que Squid Game !</h5>
            <p>
              Découvrez Dr. Brain, la nouvelle pépite sud-coréenne sur Apple TV+
            </p>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<style scoped>
.titlePage {
  padding-left: 3.25rem;
  padding-right: 1.25rem;
  padding: 1.25rem 0.625rem 0;
  display: block;
  text-align: center;
  margin-bottom: 0.9375rem;
}
.title {
  font-size: 50px;
  font-weight: bold;
  font-family: Arial, Sans-Serif;
}
</style>
