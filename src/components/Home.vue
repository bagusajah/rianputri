<template>
<div id="home" class="uk-background-cover uk-overflow-hidden uk-padding-large uk-padding-remove-bottom uk-padding-remove-horizontal">
  <div class="uk-flex uk-visible@l">
    <div class="uk-card uk-animation-slide-bottom-medium uk-width-xlarge" uk-parallax="target: #home; y: 250; sepia: 40;easing: 0;" style="height:calc(100vh - 150px)">
      <img src="../assets/images/couple.png" alt="Couple" class="uk-width-xlarge" style="position:absolute;bottom:0;left:15px;">
    </div>
    <div class="uk-width-expand uk-margin-auto uk-margin-auto-vertical uk-padding-small">
      <h1 class="uk-text-center uk-h1 uk-animation-slide-top home" uk-parallax="target: #home; y: 300;blur: 0,05;easing: 0;">{{ title }}</h1>
      <p class="uk-text-center uk-padding-large uk-animation-slide-top uk-padding-remove-top uk-padding-remove-bottom uk-h3 home" uk-parallax="target: #home; y: 200; blur: 0,05;easing: 0;">{{ deskripsi }}</p>
    </div>
  </div>
  <div class="uk-hidden@l">
    <div class="uk-card uk-responsive-height uk-animation-slide-bottom-medium" uk-parallax="target: #home; y: 250; sepia: 40;easing: 0;">
      <img src="../assets/images/couple.png" alt="Couple" class="uk-padding-small uk-padding-remove-top">
    </div>
    <div class="uk-responsive-width uk-margin-auto uk-margin-auto-vertical uk-padding-medium">
      <h1 class="uk-text-center uk-h1 uk-animation-slide-top home" uk-parallax="target: #home; y: 300;blur: 0,05;easing: 0;">{{ title }}</h1>
      <p class="uk-text-center uk-padding-large uk-animation-slide-top uk-padding-remove-top uk-h3 home" uk-parallax="target: #profile; y: 200; blur: 0,05;easing: 0;">{{ deskripsi }}</p>
    </div>
  </div>
</div>
</template>

<script>
export default {

  name: 'Home',

  data () {
    return { title: 'Wedding Invitation', deskripsi: 'Teruntuk keluarga, kerabat, teman dan rekan tercinta. Tanpa mengurangi rasa hormat, izinkan kami menyampaikan kabar bahagia bahwa kami akan melaksanan pernikahan. Dalam situasi yang penuh dengan keterbatasan, kami memohon doa restu dan dukungan agar niat kami dapat berjalan dengan lancar.' }
  }
}
</script>
<style lang="scss" scoped>
  $colorprimary : #dd183f;

  #home {
    background-image: url('../assets/images/bg.jpg');
    mix-blend-mode: multiply !important;
  }
  .home{
    color: #FFFFFF !important;
    opacity: 0;
  }
  .uk-h1 {
    font-size: 70px !important;
  }

  @media screen and (max-width: 1024px) {
    #home {
      margin-bottom: 0px !important;
    } 
    .uk-h1 {
      font-size: 47px !important;
    }
  }
</style>