<template>
  <div>
    <!-- Footer Section Begin -->
    <footer class="footer-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-5 text-left">
            <div class="footer-left">
              <div class="footer-logo">
                <router-link to="/"
                  ><img src="img/logo_website_shayna_white.png" alt=""
                /></router-link>
              </div>
              <ul>
                <li>
                  Tidak Ada Toko Offline, Tapi kami berada di Tangerang Selatan,
                  Banten, Indonesia. 14516
                </li>
                <li>Instagram : @ZharfaWaistbag.co</li>
                <li>Gmail: ariqsaja99@gmail.com</li>
              </ul>
              <div class="footer-social">
                <router-link to="/"><i class="fa fa-facebook"></i></router-link>
                <a href="https://www.instagram.com/zharfawaistbag.co/"
                  ><i class="fa fa-instagram"></i
                ></a>
                <router-link to="/"><i class="fa fa-twitter"></i></router-link>
                <router-link to="/"><i class="fa fa-pinterest"></i></router-link>
              </div>
            </div>
          </div>
          <div class="col-lg-3 offset-lg-1 text-right">
            <div class="footer-widget">
              <h5>Information</h5>
              <ul>
                <li><router-link to="/">About Us</router-link></li>
                <li><router-link to="/">Checkout</router-link></li>
                <li><router-link to="/">Contact</router-link></li>
                <li><router-link to="/">Serivius</router-link></li>
              </ul>
            </div>
          </div>
          <div class="col-lg-3">
            <div class="footer-widget text-right">
              <h5>My Account</h5>
              <ul>
                <li><router-link to="/">My Account</router-link></li>
                <li><router-link to="/">Contact</router-link></li>
                <li><router-link to="/">Shopping Cart</router-link></li>
                <li><router-link to="/">Shop</router-link></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="copyright-reserved">
        <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <div class="copyright-text">
                Copyright &copy; 2020 - 2021
                <!-- <script>
                                document.write(new Date().getFullYear());
                            </script> -->
                All rights reserved | ZharfaWaistbag.co
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <!-- Footer Section End -->
  </div>
</template>
<script>
export default {
  name: "FooterShayna",
};
</script>
