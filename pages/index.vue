<template>
  <div>
    <MyHeader/>
    <div class="wrapper">
      <div style="display: flex; align-items: center; gap: 8px;">
        <img src="~/assets/images/appgallery.png" style="width:60px; height:60px" ></img>
        <h2>App Gallery</h2>
      </div>
      <div class="items">

        <div class="item">
          <img src="~/assets/images/authenticator.jpg" alt="" title="" />
          <h4>认证器</h4>
          <p>身份验证器通过在您登录时添加第二步验证，为您的在线账户提供额外的安全保护。</p>
        </div>

        <div class="item">
          <img src="https://appimg2.dbankcdn.com/application/icon144/65/246010f65c70436c83b6d4d9158887f6.png" alt="" title="" />
          <h4>扫一扫</h4>
          <p>只需对准您想扫描的二维码或条形码，应用程序就会自动检测并扫描该码。</p>
        </div>

        <div class="item">
          <img src="~/assets/images/whitenoise.webp" alt="" title="" />
          <h4>睡眠声音</h4>
          <p>您可以通过睡眠声音、自然声音、雨声、冥想声音和白噪音等放松身心并入睡，还包括更多其他声音。</p>
        </div><!-- item -->
        <div class="item">
          <img src="~/assets/images/wheel.webp"" alt="" title="" />
          <h4>决策</h4>
          <p>决策"帮助您在各种可用选项中进行选择。您可以在不同的轮盘中输入2到50个选项，并随时使用它们</p>
        </div><!-- item -->





      </div><!-- items -->
      <h4>以及更多优秀的应用正在开发中。</h4>
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
