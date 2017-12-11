<template lang="html">
  <div class="twtter-content">
    <div class="blank2">
    </div>

    <div class="trends-tweets-container">
      <div class="trends-container">
        <div class="trends-container-title">
          <span class="span-title">Top Trends</span>
        </div>
        <div class="for-trends">
          <ul>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/purplestart.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="false" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/purplestart.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="false" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/purplestart.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/start.png" v-show="false" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>
            <li>
              <a href="#">
                <span class="trends-img"><img src="../../assets/img/tag.png" width="13px;" alt=""></span>
                <span class="trends-span" data-tippy-html="#tippy" data-tippy-interactive="true"  v-tippy="{  placement : 'top', arrow: true, interactive: true}">#ThanksGiving</span>
                <span class="tweets-numbers-start"><img src="../../assets/img/purplestart.png" v-show="true" width="13px;" alt=""></span>
                <span class="tweets-numbers-span">199,999</span>
              </a>
            </li>






          </ul>
        </div>
      </div>
      <div class="tweets-numbers-container">

        <div class="numbers-container">
          <div class="numbers-container-left">
            <div class="numbers-container-up">
              <i-count-up :start="0" :end="120500" :decimals="0" :duration="2.5" :options="options" :callback="callback"></i-count-up>
            </div>
            <div class="numbers-container-down">
              TRENDS
            </div>
          </div>
          <div class="numbers-container-right">
            <div class="numbers-container-up">
              <i-count-up :start="0" :end="190092990" :decimals="0" :duration="2.5" :options="options" :callback="callback"></i-count-up>
            </div>
            <div class="numbers-container-down">
              TWEETS
            </div>
          </div>
        </div>
        <div class="tweets-container">
          <div class="tweets-container-title">
            <span class="model-title"><img style="width: 17px; height: 14px; margin-right: 7px; margin-left:15px;" src="../../assets/img/tweet.gif">Most Recent Tweets</span>
          </div>

            <ul>

              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>

              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>

              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>

              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>


              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>


              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>

              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
              <li class="tweets-container-content-li">
                <div class="tweets-user-img">
                    <a class="userpreview" href="#" target="_blank" style="color: #333333;"><img src="http://pbs.twimg.com/profile_images/625724307432300544/WmqQSCYE_normal.jpg" class="avatarMini"></a>
                </div>
                <div class="tweets-user-content">
                  <div class="tweets-user-content-up">
                    <span class="user-name"><a href="#">Bill Bateman</a></span>
                    <span class="account-name"><a href="#">@BillBateman</a></span>
                    <span class="tweets-time">4:49 PM - 10 Dec 2017</span>
                  </div>
                  <div class="tweets-user-content-down">
                    Serious about using Twitter for marketing your business? You have to see what Cindy Donovan has developed
                    <a href="#" skip_urls="">#twittermarketing</a>
                    <a href="#" target="_blank">jvz5.com/c/10008/263555</a>
                  </div>
                </div>
              </li>
            </ul>
        </div>
      </div>
    </div>

    <div class="index-footer">
      Copy © 2017  Computational Social Science Lab (CSSL)
    </div>

    <!-- tippy -->
    <div id="tippy" style="display:none;" v-tippy-html>
        <div>
          <br />
          <a style="display: block; width: 140px; height: 26px; background-color: #1E7EBE; color: white; opacity: 1; font-size: 14px; text-decoration:none; line-height:26px;font-weight:600; cursor: pointer;">Deeply Analyze</a>
          <br />
          <a style="display: block; width: 140px; height: 26px; background-color: #468847; color: white; opacity: 1; font-size: 14px; text-decoration:none; line-height:26px;font-weight:600; cursor: pointer;">Daily Analyze</a>
          <br />
        </div>
    </div>
  </div>
</template>

<script>
import ICountUp from 'vue-countup-v2'
export default {
  name: 'Index',
  components: {
      ICountUp
    },
    data() {
      return {
        options: {
          useEasing: true,
          useGrouping: true,
          separator: ',',
          decimal: '.',
          prefix: '',
          suffix: ''
        }
      }
    },
    methods: {
      callback: function(ins) {
        ins.update(ins.endVal + 5)
      }
   }
}
</script>

<style lang="css" scoped>
  .twtter-content {
    width: 100%;
    height: 600px;
    background-color: #eef0f1;
    background-color: #ffffff;
  }
  .blank2 {
    width: 100%;
    height: 70px;
  }
  .trends-tweets-container {
    width: 80%;
    height: 500px;
    margin: auto;
    /*background-color: rgba(1, 1, 1, 0.1)*/
  }
  .trends-container {
    width: 30%;
    height: 500px;
    float: left;
    margin: 0px;
    padding: 0px;
  }
  .trends-container-title {
    width: 100%;
    height:40px;
    background-color: #f6f8fa;
    border: 1px solid rgba(27,31,35,0.15);
    border-bottom: 0;
    border-radius: 3px 3px 0 0;
    margin: 0px;
    padding: 0px;
    line-height: 40px;
  }
  .span-title {
    margin-left: 15px;
    font-size: 14px;
    color: #24292e;
    font-weight: 600;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  }
  .for-trends {
    width: 100%;
    height: 460px;
    border: 1px solid #d1d5da;
    border-top: 0px;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px;
    /*overflow-y: scroll;*/
  }
  .for-trends ul {
    width: 100%;
    list-style: none;
    padding: 0px;
    margin: 0px;

  }
  .for-trends ul li {
    display: list-item;
    text-align: -webkit-match-parent;
    border-top: 1px solid #d1d5da;
    height: 33px;
    padding-top: 10px;
  }
  .for-trends ul li a {
    color: #0366d6;
    font-size: 14px;
    text-decoration: none;

  }
  .trends-span {
    margin-left: 5px;
  }
  .trends-img {
    margin-left: 10px;
  }
  .tweets-numbers-start {
    width: 24px;
    float: right;
    height: 24px;
    line-height: 24px;
    margin-right: 10px;
    padding-left: 3px;
    padding-right: 3px;
  }
  .tweets-numbers-span {
    background-color: #468847;
    font-size: 11.049999999999999px;
    font-weight: bold;
    color: #ffffff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
    /*padding: 2px 4px 3px;*/
    border-radius: 3px;
    float: right;
    height: 24px;
    line-height: 24px;
    margin-right: 10px;
    padding-left: 3px;
    padding-right: 3px;

  }

  .tweets-numbers-container {
    width: 60%;
    height: 500px;
    float: right;
    /*background-color: rgba(1, 33, 123, 0.1)*/
  }

  .numbers-container {
    width: 80%;
    height: 140px;
    margin: auto;
    /*background-color: rgba(2,3,4,0.1)*/
  }
  .numbers-container-left {
    width: 45%;
    height: 140px;
    float: left;
  }
  .numbers-container-right {
    width: 45%;
    height: 140px;
    float: right;
  }
  .numbers-container-up {
    width: 100%;
    height: 80px;
    text-align: center;

    color: rgb(0, 174, 239);
    font-size: 40px;
    letter-spacing: 2px;
    font-weight: 400;
  }
  .numbers-container-down {
    width: 100%;
    height: 45px;
    line-height: 10px;
    font-size: 28px;
    text-align: center;
    letter-spacing: 1px;
    font-weight: 500px;
    font-family: Poppins, Helvetica, Arial, sans-serif;
    color: rgba(17, 17, 17, 0.7);
    /*background-color: blue;*/
  }
  .tweets-container {
    width: 100%;
    height: 360px;
    border: 1px solid #d1d5da;
    border-top: 0px;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px;

  }
  .tweets-container-title {
    width: 100%;
    height: 40px;
    line-height: 40px;
    background-color: #1E7EBE;
    border: 1px solid rgba(27,31,35,0.15);
    border-left: 0px;
    border-right: 0px;
    border-bottom: 0;
    border-radius: 3px 3px 0 0;

  }
  .model-title {
    color: rgb(255, 255, 255);
    font-size: 18px;
    font-weight: 600;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";

  }
  .tweets-container ul {
    width: 100%;
    margin: 0px;
    padding: 0px;
    list-style: none;
    height: 310px;
    overflow-y: auto;

  }
  .tweets-container ul li{
    width: 100%;
    display: list-item;
    text-align: -webkit-match-parent;
    border-bottom: 1px solid #d1d5da;
    padding-top: 10px;
    padding-bottom: 5px;
    overflow: auto;
    min-height: 50px;
  }
  .tweets-user-img {
    width: 8%;
    float: left;
    margin-left: 10px;
  }
  .tweets-user-img a{
    text-decoration: none;
  }
  .tweets-user-content {
    width: 90%;
    float: right;
    /*margin-right: 1px;*/
  }
  .user-name a{
    color: #333333;
    text-decoration: none;
    font-weight: bold;
    font-size: 12px;
  }
  .account-name a {
    color: #999;
    text-decoration: none;
    font-size: 12px;
  }
  .tweets-time {
    color: #999;
    font-size: 12px;
  }
  .tweets-user-content-down {
    color: rgb(51, 51, 51);
    font-size: 11px;
    line-height: 14px;
  }
  .tweets-user-content-down a {
    color: #0088cc;
    text-decoration: none;
  }
  .index-footer {
    background-color: #2f3539;
    border-top: 1px solid #393f43;
    width: 100%;
    height: 130px;
    line-height: 130px;
    font-size: 16px;
    color: #cecece;
    text-align: center;
    margin-top: 80px;
  }
</style>
