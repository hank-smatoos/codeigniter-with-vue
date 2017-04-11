<template>
  <div class="flex-center position-ref full-height">
    <div class="content">
      <div class="imgs m-b-md">
        <img src="/assets/images/codeigniter.png"
             alt="">3.1.3
        <i class="fa fa-times and"
           aria-hidden="true"></i>
        <img src="/assets/images/vue.png"
             alt="">2.0
      </div>

      <div class="links">
        <a href="https://codeigniter.org.tw/userguide3/">CodeIgniter3.1.3 Documentation</a>
        <a href="https://cn.vuejs.org/v2/guide/">Vue2.0 Documentation</a>
        <a href="https://github.com/shana0440/codeigniter-with-vue">Github</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Hello World!!'
    }
  }
}
</script>

<style lang="sass">
html, body
  background-color: #fff
  color: #636b6f
  font-family: 'Roboto', sans-serif
  font-weight: 100
  height: 100vh
  margin: 0

.full-height
  height: 100vh

.flex-center
  align-items: center
  display: flex
  justify-content: center

.position-ref
  position: relative

.top-right
  position: absolute
  right: 10px
  top: 18px

.imgs img
  height: 100px

.content
  text-align: center

.title
  font-size: 84px

.links > a
  color: #636b6f
  padding: 0 25px
  font-size: 12px
  font-weight: 600
  letter-spacing: .1rem
  text-decoration: none
  text-transform: uppercase

.m-b-md
  margin-bottom: 30px

.and
  font-size: 50px
  vertical-align: super
</style>
