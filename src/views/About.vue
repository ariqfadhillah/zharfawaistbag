<template>
  <div>
    <div class="pic-box">
      <pic-zoom url="img/banner-2.jpg" :scale="3.6"></pic-zoom>
    </div>

    <div class="pic-box">
      <zoom-on-hover img-normal="img/banner-2.jpg" :scale="6"></zoom-on-hover>
    </div>
  </div>
</template>

<script>
import PicZoom from "vue-piczoom";

export default {
  name: "App",
  components: {
    PicZoom,
  },
};
</script>

<style scoped>
.pic-box {
  width: 500px;
  height: 500px;
}

.zoom-on-hover {
  position: relative;
  overflow: hidden;
}
.zoom-on-hover .normal {
  width: 100%;
}
.zoom-on-hover .zoom {
  position: absolute;
  opacity: 0;
  transform-origin: top left;
}
.zoom-on-hover.zoomed .zoom {
  opacity: 1;
}
.zoom-on-hover.zoomed .normal {
  opacity: 0;
}
</style>
