<template>
  <div>
    <MyHeader/>
    <div class="wrapper">
      <h2>Huawei Gallery</h2>
      <div class="items">

        <div class="item">
          <img src="https://appimg2.dbankcdn.com/application/icon144/65/246010f65c70436c83b6d4d9158887f6.png" alt="" title="" />
          <h4>QR & Barcode Scanner</h4>
          <p>The fastest QR and Barcode scanner</p>
          <a href="https://appgallery.huawei.com/app/C102171019" class="google-play-link"><img src="~/assets/images/huawei-app-gallery.png" alt="" title="" /></a>
        </div><!-- item -->




      </div><!-- items -->
    </div>
    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from "../components/MyHeader";
import MyFooter from "../components/MyFooter";
export default {
  name: 'IndexPage',
  components: {MyFooter, MyHeader}
}
</script>
<style>
@import "assets/css/style.css";
</style>
