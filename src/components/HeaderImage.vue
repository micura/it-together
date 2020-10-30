<template>
  <div class="container-fluid px-0 js-fullheight">
    <div class="d-md-flex no-gutters slider-text js-fullheigh">
      <img class="js-fullheight img-fluid" src="@/assets/images/logo.svg">
      <div class="d-flex align-items-center mx-auto">
        <div class="header-text mt-5">
          <h1 class="mb-3 brand-text"><span>IT-Together</span></h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import $ from 'jquery'

export default {
  name: "HeaderImage",
  props: {}
};

var fullHeight = function() {
    $('.js-fullheight').css('height', $(window).height());
    $(window).resize(function(){
        $('.js-fullheight').css('height', $(window).height());
    });
};
fullHeight();
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header-text {
    color: #315eff;
    font-size: 60px;
}
/*
.brand-text {
    display: none;
} */
</style>
