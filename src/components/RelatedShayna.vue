<template>
  <div>
    <!-- Related Products Section End -->
    <div class="related-products spad">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="section-title">
              <h2>Related Products</h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-3 col-sm-6">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-1.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                  </li>
                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Coat</div>
                <router-link to="/product">
                  <h5>EPSILON 23L Rolltop Backpack</h5>
                </router-link>
                <div class="product-price">
                  411.000 IDR
                  <span>411.000 IDR</span>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-2.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                  </li>
                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Rucksack</div>
                <router-link to="/product">
                  <h5>FEDORA 20L Rucksack</h5>
                </router-link>
                <div class="product-price">
                  350.000 IDR
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-3.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                  </li>
                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Camera Sling Bag</div>
                <router-link to="/product">
                  <h5>METEORA 5.5L Camera Sling Bag</h5>
                </router-link>
                <div class="product-price">
                  259.000 IDR
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/products/women-4.jpg" alt="" />
                <ul>
                  <li class="w-icon active">
                    <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                  </li>
                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Waistpack</div>
                <router-link to="/product">
                  <h5>PRESTA Z 4L Waistpack</h5>
                </router-link>
                <div class="product-price">
                  289.000 IDR
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Related Products Section End -->
  </div>
</template>

<script>
export default {
  name: "RelatedShayna",
  components: {
    // carousel,
  },
};
</script>
