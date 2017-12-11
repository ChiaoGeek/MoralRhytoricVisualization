<template lang="html">
  <div class="header-banner">
    <div id="headernav" class="header-section" v-bind:class="{blackNav: ifScroll == true}">
      <div class="header-container">
        <div class="header-container-left">
          <a href="#">Moral Rhytoric</a>
        </div>
        <div class="header-container-right">
          <ul class="ul-nav">
            <li ><a class="active" href="">Features</a></li>
            <li><a href="">Pricing</a></li>
            <li><a href="">Blog</a></li>
            <li><a href="">Login</a></li>
            <li><a href="" >Try It Free</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="banner-section">
      <div class="blank1">

      </div>
      <div class="banner-search">
        <form method="post">
          <input type="text" class="textbox" placeholder="Search">
          <input title="Search" value="Search" type="submit" class="button">
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'headerIndex',
  data () {
    return {
      ifScroll: false
    }
  },
  computed: {},
  mounted () {
    var that = this
    var scrollRecord = that.getScrollTop()
    console.log(that.getScrollTop())
    window.document.body.onscroll = function() {
      if (that.getScrollTop() > 0){
        if (scrollRecord - that.getScrollTop() > 0){
          if (that.getScrollTop() <= 65){
            // headernav.style.opacity = that.getScrollTop() / 65
            headernav.style.backgroundColor = "rgba(34, 34, 34, "+that.getScrollTop() / 65+")"
            scrollRecord = that.getScrollTop()
          }
        }else {
          // headernav.style.opacity = that.getScrollTop() / 65

          headernav.style.backgroundColor = "rgba(34, 34, 34, "+that.getScrollTop() / 65+")"
          // console.log(headernav.style.backgroundColor)
          scrollRecord = that.getScrollTop()
        }
      }else if(that.getScrollTop() == 0) {
          headernav.style.backgroundColor = "rgba(34, 34, 34, 0)"
      }
    }
  },
  methods: {
    getScrollTop: function() {
      var scrollPos
      if (window.pageYOffset) {
        scrollPos = window.pageYOffset
      }
      else if (document.compatMode && document.compatMode != 'BackCompat')  {
        scrollPos = document.documentElement.scrollTop
      } else if (document.body) {
        scrollPos = document.body.scrollTop
      }
      return scrollPos
    }
  },
  components: {}
}
</script>

<style lang="css" scoped>
  .header-banner {
    width: 100%;
    height: 415px;
    background: url('../../assets/img/banner.jpg') center top no-repeat;
    background-attachment: scroll;
    background-size: cover;
    margin: 0px;
    padding: 0px;
  }
  .header-section {
    width: 100%;
    height: 65px;
    background-color: rgba(34, 34, 34, 0);
    position: fixed;
    top: 0px;
    margin: 0px;
    padding: 0px;
    /*opacity: 0;*/
  }
  .header-container {
    width: 61.4%;
    height: 65px;
    margin: auto;
    position: relative;
    /*opacity: inherit;*/

  }
  .header-container-left {
    width: 30%;
    height: 65px;
    float: left;
    line-height: 65px;
    opacity: 1;
  }
  .header-container-left a {
    color: #fff;
    font-size: 24px;
    font-weight: 700;
    font-family: 'Roboto', sans-serif;
    text-decoration: none;
    opacity: 1;
  }
  .header-container-right {
    width: 60%;
    height: 65px;
    float: right;
    line-height: 65px;
  }
  .ul-nav {
    padding: 0px;
    margin: 0px;
    display: block;
  }
  .active {
    color: #ccc!important;
  }
  .ul-nav li {
    float: left;
    position: relative;
    display: block;
    font-family: 'Roboto', sans-serif;
    font-size: 14px;
    height: 65px;
    margin-left: 30px;
  }
  .ul-nav li a{
    line-height: 65px;
    height: 65px;
    display: block;
    color: #fff;
    font-size: 14px;
    line-height: 65px;
    text-transform: uppercase;
    font-weight: 700!important;
    text-decoration: none;
    /*background-color: red;*/
    text-align: center;
  }
  .ul-nav li a:hover {
    color: #ccc;
  }

  .banner-section {
    width: 100%;
    height: 350px;
  }
  .blank1 {
    width: 100%;
    height: 180px;
  }
  .banner-search {
    width: 60%;
    height: 100px;
    margin: auto;
  }
  form {
  outline: 0;
  -webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  -webkit-border-radius: 4px;
  border-radius: 4px;
  display: block;
  margin: auto;
  text-align: center;
}

form > .textbox {
  display: block;
  margin: auto;
  outline: 0;
  height: 42px;
  width: 78%;
  line-height: 42px;
  padding: 0 16px;
  background-color: rgba(255, 255, 255, 0.8);
  color: #212121;
  border: 0;
  float: left;
  -webkit-border-radius: 4px 0 0 4px;
  border-radius: 4px 0 0 4px;
  font-size: 20px;
  margin: auto;
  margin-left: 5%;
}

form > .textbox:focus {
  outline: 0;
  background-color: #FFF;
}

form > .button {
  outline: 0;
  background: none;
  background-color: rgba(38, 50, 56, 0.8);
  float: left;
  height: 42px;
  width: 84px;
  text-align: center;
  line-height: 42px;
  border: 0;
  color: #FFF;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: 16px;
  text-rendering: auto;
  text-shadow: 0 1px 1px rgba(0, 0, 0, 0.2);
  -webkit-transition: background-color .4s ease;
  transition: background-color .4s ease;
  -webkit-border-radius: 0 4px 4px 0;
  border-radius: 0 4px 4px 0;
}

form > .button:hover {
  background-color: rgba(0, 150, 136, 0.8);
}
</style>
