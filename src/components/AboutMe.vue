<template>
  <div class="" style="width: 100%">
    <div class="content-video">
      <h4 class="head-about"><b>ABOUT ME</b></h4>
      <div class="m-v-30 img-border">
        <img src="../../public/assets/image/me.jpg" style="border-radius: 50%; height: 200px; width: 200px; object-fit: cover;" alt="">
      </div>
      <div class="m-v-30">
        <h5>Haryor Rahmadityo</h5>
      </div>
      <div class="m-v-10">
        <p>"AkU adalah orang gila sekalii yaaa"</p>
      </div>
      <div class="m-v-20">
        <button type="button" class="btn btn-primary btn-about" name="button">ABOUT ME</button>
      </div>
    </div>
    <video-bg :sources="['assets/video.mp4']" img="https://cdn-images-1.medium.com/max/1200/1*mP3ujHhKk-yFDsRntcapPw.png">
      <!-- If you want to add content here, a slot is waiting! -->
    </video-bg>
  </div>
</template>

<script>
import VideoBg from 'vue-videobg'

export default {
  name: 'AboutMe',
  props: {
    data : String
  },
  components: {
    'video-bg' : VideoBg
  }
}
</script>

<style lang="css">
  .VideoBg::after {
    content: '\A';
    position: absolute;
    width: 100%; height:100%;
    top:0; left:0;
    background:rgba(0, 0, 0, 0.7);
    opacity: 1;
    transition: all 1s;
    -webkit-transition: all 1s;
    z-index: 99;
  }

  .content-video{
    -webkit-transform: skewX(15deg);
    -ms-transform: skewX(15deg);
    transform: skewX(15deg);
    color: white;
    width: 50%;
    left: 0;
    right: 0;
    margin: auto;
    height: 100vh;
    background-image: linear-gradient(-90deg, rgb(0, 0, 0, 0.6), rgb(0, 0, 0, 0.8),rgb(0, 0, 0, 0.8),
    rgb(0, 0, 0, 0.8),rgb(0, 0, 0, 0.8),rgb(0, 0, 0, 0.8),rgb(0, 0, 0, 0.8), rgb(0, 0, 0, 0.8), rgb(0, 0, 0, 0.6));
    position: absolute;
    z-index:999;
    /*opacity: 0.7;*/
    text-align: center;
    padding: 40px 10px;
  }

  .content-video .img-border {
    border: 1px solid rgb(249, 249, 249, 0.1);
    padding: 20px 0;
    margin-left: 20px;
    margin-right: 20px;
  }

  .head-about{
    display: inline;
    color: #7986cb;
    padding-bottom: 10px;
    border-bottom: 1px solid #7986cb;
  }

  .img-about {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    background-color: blue;
    align-self: center;
  }
</style>
