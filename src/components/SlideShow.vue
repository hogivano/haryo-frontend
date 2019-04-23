<template>
  <div class="">
    <div style="position:absolute; top:0; z-index: 9; padding: 10px 10%; width: 100%" class="nav">
      <div class="">
        <ul toggleable class="nav">
          <b-nav-item active>Home</b-nav-item>
          <b-nav-item>About Me</b-nav-item>
        </ul>
      </div>
      <b-navbar-brand class="mx-auto" style="text-align:center">
        <img src="../../public/assets/image/logo-putih.png" style="height: 80px" class="d-inline-block align-top" alt="Logo">
      </b-navbar-brand>
      <div>
        <ul class="nav" toggleable>
          <b-nav-item active>Postofolio</b-nav-item>
          <b-nav-item>My Album</b-nav-item>
        </ul>
      </div>
    </div>

      <carousel autoplay :perPageCustom="[[1024, 1]]">
        <slide>
          <img src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" style="width: 100%; max-width: 100%; min-height: 100vh">
        </slide>
        <slide>
          <img src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" style="width: 100%; max-width: 100%; min-height: 100vh">
        </slide>
        <slide>
          <img src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" style="width: 100%; max-width: 100%; min-height: 100vh">
        </slide>
        <slide>
          <img src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" style="width: 100%; max-width: 100%; min-height: 100vh">
        </slide>
      </carousel>
  </div>
</template>

<script>
export default {
  name: 'SlideShow',
  props: {
    data : String
  }
}
</script>

<style lang="css">
  .VueCarousel {
    height: 100vh !important;
  }
  .VueCarousel-pagination {
    position: absolute !important;
    bottom: 20px !important;
    z-index: 999;
    display: block !important;
  }

  .nav-link {
    color: white;
  }

  .nav-link:hover {
    border-bottom: 1px solid white;
    color: white;
  }
</style>
