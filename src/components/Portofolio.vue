<template>
  <div class="" style="width: 100%">
    <div class="my-album">
      <div class="row">
        <div class="col-md-3">
          <img src="../../public/assets/image/surabaya.jpg" alt="">
          <div class="info">
            <h5><b>SURABAYA</b></h5>
          </div>
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/madura.jpg" alt="">
          <div class="info">
          </div>
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/gresik.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/lamongan.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/malang.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/sidoarjo.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/madura.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/jedih.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/surabaya.jpg" alt="">
          <div class="info">
            <h5><b>SURABAYA</b></h5>
          </div>
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/madura.jpg" alt="">
          <div class="info">
          </div>
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/gresik.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/lamongan.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/malang.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/sidoarjo.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/madura.jpg" alt="">
        </div>
        <div class="col-md-3">
          <img src="../../public/assets/image/jedih.jpg" alt="">
        </div>
      </div>
    </div>
    <!-- <div class="content-portofolio">
      <div class="container">
        <div>
          <b-nav tabs>
            <b-nav-item active>Adventure</b-nav-item>
            <b-nav-item>Nature</b-nav-item>
            <b-nav-item>Arcade</b-nav-item>
          </b-nav>
        </div>
        <div class="content">
          <div class="row">
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
              <div class="info">
              </div>
            </div>
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
              <div class="info">
              </div>
            </div>
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
            </div>
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
            </div>
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
            </div>
            <div class="col-md-3">
              <img src="../../public/assets/image/me.jpg" alt="">
            </div>
          </div>
          <div class="m-v-30">
            <button type="button" class="btn btn-white" name="button">See All</button>
          </div>
        </div>
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: 'portofolio'
}
</script>

<style lang="css" scoped>
  .content-portofolio {
    background-color: #161616;
    color: #f5f5f5;
  }

  .content-portofolio .container {
    padding: 30px;
  }

  .content-portofolio .container .content {
    padding: 30px 20px;
  }

  .content-portofolio .container .content .row div {
    padding: 0;
  }

  .content-portofolio .container .content .row img{
    width: 100%;
    height: 250px;
    object-fit: cover;
  }

  .content-portofolio .container .content .row .info {
    position:absolute;
    background-color:rgb(0, 0, 0, .9);
    width: 100%;
    height: 100%;
    z-index: 1;
  }

  .my-album .row{
    width: 100%;
    margin: 0;
  }

  .my-album .row .col-md-3 {
    padding: 0 !important;
  }

  .my-album .row .col-md-3 img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    object-position: center;
  }

  .my-album .row .info {
    position:absolute;
    width: 100%;
    z-index: 1;
    color: white;
  }

</style>
