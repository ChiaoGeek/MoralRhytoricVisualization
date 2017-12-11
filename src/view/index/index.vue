<template lang="html">
  <div class="twtter-content">
    <div class="blank2">
    </div>

    <div class="trends-tweets-container">
      <div class="trends-container">

      </div>
      <div class="tweets-numbers-container">
        <div class="numbers-container">

        </div>
        <div class="tweets-container">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Index'
}
</script>

<style lang="css" scoped>
  .twtter-content {
    width: 100%;
    height: 600px;
    background-color: #eef0f1;
  }
  .blank2 {
    width: 100%;
    height: 70px;
  }
  .trends-tweets-container {
    width: 80%;
    height: 500px;
    background-color: rgba(255, 0, 0, 0.2);
    margin: auto;
  }
  .trends-container {
    width: 40%;
    height: 500px;
    float: left;
    background-color: rgba(123, 210, 1, 0.3)
  }
  .tweets-numbers-container {
    width: 60px;
  }


</style>
