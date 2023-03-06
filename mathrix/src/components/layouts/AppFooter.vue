<template>
  <footer class="footer">
    <div class="footer-top">
      <div class="container d-flex justify-content-center align-items-center flex-column">
        <icon-leaf />
        <h1 class="footer-top__header">Use the app to review anywhere</h1>
        <div class="footer-top__images d-flex">
          <icon-google-play class="me-7" />
          <img src="../../../assets/images/footer/app.svg" alt="App Store Image" />
        </div>
      </div>
    </div>
    <div class="footer-main container">
      <div class="row">
        <div class="col-2">
          <icon-footer-logo />
        </div>
        <div class="col-2">
          <ul>
            <li>Classes</li>
            <li>5th</li>
            <li>4th</li>
            <li>3rd</li>
            <li>Second</li>
            <li>First</li>
            <li>Terminal L</li>
            <li>Terminal S</li>
            <li>Terminal X</li>
          </ul>
        </div>
        <div class="col-2">
          <ul>
            <li>Subjects</li>
            <li>Mathematics</li>
            <li>Physical</li>
            <li>SVT</li>
            <li>French</li>
            <li>First</li>
            <li>Chemistry</li>
            <li>Technology</li>
          </ul>
        </div>
        <div class="col-2">
          <ul>
            <li>Company</li>
            <li>About us</li>
            <li>Contact us</li>
            <li>Help</li>
            <li>Support Community</li>
            <li>Share your story</li>
          </ul>
        </div>
        <div class="col-4">
          <ul>
            <li>Follow us</li>
            <li>
              <div>
                <button class="btn me-4">
                  <icon-facebook />
                </button>
                <button class="btn">
                  <icon-youtube />
                </button>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import IconLeaf from "../icons/IconLeaf.vue";
import IconGooglePlay from "../icons/IconGooglePlay.vue";
import IconFooterLogo from "../icons/IconFooterLogo.vue";
import IconFacebook from "../icons/IconFacebook.vue";
import IconYoutube from "../icons/IconYoutube.vue";

export default {
  name: "AppFooter",
  components: { IconYoutube, IconFacebook, IconFooterLogo, IconGooglePlay, IconLeaf }
};
</script>

<style scoped>

</style>