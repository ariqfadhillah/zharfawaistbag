<template>
  <div class="home">
    <HeaderShayna />
    <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="breadcrumb-text product-more text-left">
              <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
              <span>Detail</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <section class="product-shop spad page-details">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="row">
              <div class="col-lg-6">
                <div class="product-pic-zoom">
                  <pic-zoom
                    class="product-big-img"
                    :scale="2"
                    :url="gambar_default"
                  />
                </div>
                <div class="product-thumbs">
                  <carousel
                    class="product-thumbs-track ps-slider"
                    :autoplay="false"
                    :autoWidth="true"
                    :nav="false"
                    :dots="true"
                    :items="3"
                    :loop="false"
                  >
                    <div
                      class="pt"
                      @mouseover="changeImage(thumbs[0])"
                      :class="thumbs[0] == gambar_default ? 'active' : ''"
                    >
                      <img src="img/mickey1.png" alt="" />
                    </div>

                    <div
                      class="pt"
                      @mouseover="changeImage(thumbs[1])"
                      :class="thumbs[1] == gambar_default ? 'active' : ''"
                    >
                      <img src="img/mickey2.png" alt="" />
                    </div>

                    <div
                      class="pt"
                      @mouseover="changeImage(thumbs[2])"
                      :class="thumbs[2] == gambar_default ? 'active' : ''"
                    >
                      <img src="img/mickey3.png" alt="" />
                    </div>

                    <div
                      class="pt"
                      @mouseover="changeImage(thumbs[3])"
                      :class="thumbs[3] == gambar_default ? 'active' : ''"
                    >
                      <img src="img/mickey4.png" alt="" />
                    </div>
                  </carousel>
                </div>
              </div>
              <div class="col-lg-6 text-left">
                <div class="product-details">
                  <div class="pd-title">
                    <span>Rucksack</span>
                    <h3>FEDORA 20L Rucksack</h3>
                  </div>
                  <div class="pd-desc">
                    <p>
                      - Color: Black only. <br />
                      - Dimension (cm) H:44 x W:28 x D:14 <br />- Total
                      Capacity: 20L <br />- 1 main compartment + 15" padded
                      laptop sleeve with fastener. <br />- Hidden drawcord
                      closure with top cover.<br />
                      - 2 zippered front pocket. <br />- 2 extra side pockets.
                    </p>
                    <p>
                      EKSPLORASI SETIAP HARI Dengan penutup drawcord yang
                      tersembunyi, bahan bermutu tinggi, satu kompartemen besar
                      utama dengan kantung laptop berbantal 15 "dan dua saku
                      depan berritsleting, FEDORA dirancang untuk penjelajahan
                      Anda sehari-hari.
                    </p>
                    <h4>350.000 IDR</h4>
                  </div>
                  <div class="quantity">
                    <router-link
                      to="cart"
                      class="primary-btn pd-cart"
                      >Tambah Keranjang</router-link
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Product Shop Section End -->
    <RelatedShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue";
import RelatedShayna from "@/components/RelatedShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";
import carousel from "vue-owl-carousel";
import PicZoom from "vue-piczoom";

export default {
  name: "Product",
  components: {
    HeaderShayna,
    carousel,
    RelatedShayna,
    FooterShayna,
    PicZoom,
  },
  data() {
    return {
      gambar_default: "img/mickey1.png",
      thumbs: [
        "img/mickey1.png",
        "img/mickey2.png",
        "img/mickey3.png",
        "img/mickey4.png",
      ],
    };
  },
  methods: {
    changeImage(urlImage) {
      this.gambar_default = urlImage;
    },
  },
};
</script>

<style scoped>
.product-thumbs .pt {
  margin-right: 12px;
  width: 178.333px;
}
.product-big-img {
  object-fit: contain;
}
</style>
