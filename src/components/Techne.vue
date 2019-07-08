<template>
  <div >
    <div class="vara">
      <div class="vara-LOGO">
        <img src="./images/vara.png" alt="vara">
      </div>
      <div class="COMING-SOON" >
        <p>COMING SOON</p>
      </div>
      <div class="footer" >
        <p>Vara Fresh Pty Ltd</p>
        <p>480 Princes Highway, Bomaderry NSW 2541</p>
        <p>© 2019 Vara Fresh Holdings Pty Ltd</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      // reshight:0,
      msg: 'Welcome to Your Vue.js App'
    }
  },
  updated () {
    // reshight = document.documentElement.clientHeight
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus" scoped>
    #app
      height 100%
      width 100%
      & > div:nth-child(1)
        width 100%
        height 100%
      .vara
        width 100%
        height 100%
        background-color #9DD9D1
        overflow hidden
        font-family PingFangSC-Regular
        text-align center
        .vara-LOGO
          position absolute
          left 50%
          transform translateX(-50%)
          height 63%
          & > img
            display inline-block
            background-size 100% 100%
            /*width 25%*/
            height 100%
            margin-top 12%
        .COMING-SOON
          color:rgba(255,255,255,1);
          position absolute
          left 50%
          top 76%
          transform translateX(-50%)
          & > p:nth-child(1)
            font-size 14px
            font-family PingFangSC-Semibold
            font-weight 600
        .footer
          position absolute
          left 50%
          bottom 3%
          margin-top 47px
          transform translateX(-50%)
          color:rgba(255,255,255,1)
          & > p:nth-child(1)
            font-size:9px;
            font-weight:400;
          & > p:nth-child(2)
            font-size:9px;
            font-weight:400;
            margin 3px 0
          & > p:nth-child(3)
            font-size 7px
            font-weight 400
</style>
