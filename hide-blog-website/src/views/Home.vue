<template>
  <div>
    <div class="top-nav">
      <div class="top-middle">
        <div class="nav-title">Hide的Blog</div>
      </div>
    </div>
    <div class="body-wrap">
      <div class="body-right">123</div>
      
    </div>
    <div class="footer">123</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>

<style lang="scss" scoped>
.top-nav {
  height: 100px;
  box-shadow: 0px 2px 2px 2px #eee;
  position: sticky;
  top: 0;
  z-index: 100;
  .top-middle {
    width: 1080px;
    height: 100px;
    line-height: 100px;
    margin: 0 auto;
    .nav-title{
      font-size:30px;
    }
  }

}
.body-wrap {
  width: 1080px;
  min-height: 800px;
  background: #eeeeee;
  margin: 0 auto;
  position: relative;
  margin-top: 24px;
  .body-right{
    position: absolute;
    top: 0;
    right: 0;
    width: 400px;
    min-height: 400px;
    background: #999;
  }
}
</style>
