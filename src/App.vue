<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<style lang="stylus">
*
  margin: 0
  padding: 0
body
  height: 100%
  width: 100%
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50

#nav
  padding 30px
  a
    font-weight bold
    color #2c3e50
    &.router-link-exact-active
      color #42b983

.m-v-50
  margin-top: 50px
  margin-bottom: 50px

.m-v-30
  margin-top: 30px
  margin-bottom: 30px

.m-v-20
  margin-top: 20px
  margin-bottom: 20px

.m-v-10
  margin-top: 10px
  margin-bottom: 10px

.text-white
  color: white

.text-link:hover
  border-bottom-width: 1px
  border-bottom-style: solid

.btn-primary
  background-color: #3f51b5 !important

.btn-white
  border: 1px solid white !important
  color: white !important
  padding: 10px 40px !important
  font-size: 15px !important

</style>
