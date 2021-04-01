<template>
  <div>
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <carousel class="hero-items" :autoplay="true" :items="1" :nav="false">
        <div
          class="single-hero-items set-bg"
          style="background-image: url('img/hero-1.png')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Daypack Rolltop</span>
                <h1>Buruan Pesen!</h1>
                <p>
                  Produk terlaku keknya selama ini yaitu Alphat 21L - Daypack
                  Rolltop UDAH MANA (Limited Edition), pesan sekarang deh!
                  Sebelum kehabisan.
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('img/hero-2.png')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Tas Pria</span>
                <h1>WAJIB DIBACA</h1>
                <p>
                  Dijamin READY STOCK selama bisa di-BELI dan tidak ada tanda
                  PO. Sebelum melakukan order, wajib baca CATATAN TOKO di menu
                  CATATAN.
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('img/hero-3.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>CALDERA 23L  Rucksack</span>
                <h1>DAILY OUTDOOR ATMOSPHERE</h1>
                <p>
                  Apa-apaan nih, bahasa Loe Kebagusan min. Yups Tas ini udah
                  dari High-Grade water resistant polyester fabric dan muat
                  untuk Laptop 15" coba pesen sekarang.
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
      </carousel>
    </section>
    <!-- Hero Section End -->
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "HeroShayna",
  components: {
    carousel,
  },
};
</script>
