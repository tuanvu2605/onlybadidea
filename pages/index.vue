<template>
  <div>
    <MyHeader/>
    <div class="wrapper">
      <h2>Google Play</h2>
      <div class="items">

        <div class="item">
          <img src="https://lh6.ggpht.com/-LHkE5TWqK0bWUdreGY2m28wJa9YsMvkkXiL-1u7ZRcBs2gXP8bsTTpo9IWWdY1hhaw=w300" alt="" title="" />
          <h4>QR and Barcode Scanner</h4>
          <p>The fastest QR and Barcode scanner. Try it NOW!</p>
          <a href="https://play.google.com/store/apps/details?id=com.gamma.scan" class="google-play-link"><img src="~/assets/images/google-play-link.png" alt="" title="" /></a>
        </div><!-- item -->

        <div class="item">
          <img src="https://lh3.googleusercontent.com/7oyN6QKAZpo3DQ6vI8jCHEc5Gz25wVtWpAMm4nkaW1dKbwz4bxR89Yd-1rzcUzShPJdZ=s360" alt="" title="" />
          <h4>Find the Difference 1000+ levels</h4>
          <p>Find 5 differences in picture. Both easy and HARD. Can you spot the difference?</p>
          <a href="https://play.google.com/store/apps/details?id=com.gamma.find.diff" class="google-play-link"><img src="~/assets/images/google-play-link.png" alt="" title="" /></a>
        </div><!-- item -->

        <div class="item">
          <img src="https://lh3.googleusercontent.com/YnHA2Q-YH4b2CJuaEd8XyRmYJyln34NkIlZ4zKFmK1cnIHiLUUR3jFGMBVn8ASrBUo8=s360" alt="" title="" />
          <h4>Checkers</h4>
          <p>Your new challenging Checkers game. Download Now!</p>
          <a href="https://play.google.com/store/apps/details?id=com.gamma.checkers" class="google-play-link"><img src="~/assets/images/google-play-link.png" alt="" title="" /></a>
        </div><!-- item -->

        <div class="item">
          <img src="https://lh3.googleusercontent.com/-uhT-dyn3EJ0FE80wu442RJqRJFquzNxg7dSR8wlIGbK1zft4U83wuUFm2-33KxAhA=w300" alt="" title="" />
          <h4>Piano Wheel</h4>
          <p>Play Awesome Piano Wheel</p>
          <a href="https://play.google.com/store/apps/details?id=com.gamma.piano.balls" class="google-play-link"><img src="~/assets/images/google-play-link.png" alt="" title="" /></a>
        </div><!-- item -->

        <div class="item">
          <img src="https://lh3.googleusercontent.com/vdHJwvwbwl6PCfI5gek_20FiAvXeHH2Ok5zWzaWfXq1LidvSl3Hz6HyUd7ruvbJfYeCK=w300" alt="" title="" />
          <h4>Love Pixel - Color by Number</h4>
          <p>Color by Number Coloring Pages for adults and kids. Download Now!<br /> for free now</p>
          <a href="https://play.google.com/store/apps/details?id=com.gamma.pixellove" class="google-play-link"><img src="~/assets/images/google-play-link.png" alt="" title="" /></a>
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
