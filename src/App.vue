<template>
  <div class="header">
    <div class="container">
      <img class="image" src="logoAlloCine.svg" alt="image" />
    </div>
    <div id="nav">
      <router-link to="/cinema">CINÉMA</router-link> |
      <router-link to="/">SÉRIE</router-link>
    </div>
  </div>

  <!--  <nav class="navbar fixed-top navbar-expand-lg navbar-yellow bg-yellow">
    <div class="container">
      <img src="logoAlloCine.svg" alt="image" />
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#cinéma" @click="affPortfolio">CINÉMA</a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link active"
              aria-current="page"
              href="#série"
              @click="affPresentation"
              >SÉRIE</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#trailers" @click="affPortfolio"
              >TRAILERS</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#dvd" @click="affPortfolio">DVD</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#vod" @click="affPortfolio">VOD</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#kids" @click="affPortfolio">KIDS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#disney" @click="affPortfolio">DISNEY+</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>-->
  <router-view />
</template>

<style>
@import "~bootstrap/dist/css/bootstrap.min.css";
@import "~font-awesome/css/font-awesome.min.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  overflow-x: hidden;
}
.header {
  background-color: #fecc00;
}
img {
  width: 162px;
  text-align: left;
}

#nav {
  padding: 8px;
  text-align: right;
  box-sizing: border-box;
  font-size: 0.98em;
  letter-spacing: 0.2rem;
}

#nav a {
  font-weight: bold;
  color: #000;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #fff;
}
</style>
