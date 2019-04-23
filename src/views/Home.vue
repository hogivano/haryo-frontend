<template>
  <div class="home">
    <SlideShow data="Welcome to Your Vue.js App"/>
    <AboutMe data="coki"/>
    <Portofolio data="coki"/>
    <Count/>
  </div>
</template>

<script>
// @ is an alias to /src
import SlideShow from '@/components/SlideShow.vue'
import AboutMe from '@/components/AboutMe.vue'
import Album from '@/components/Album.vue'
import Portofolio from '@/components/Portofolio.vue'
import Count from '@/components/Count.vue'

export default {
  name: 'home',
  components: {
    SlideShow,
    AboutMe,
    Portofolio,
    Count
  }
}
</script>
