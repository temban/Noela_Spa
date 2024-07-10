<script>
export default {
  name: "Home",
  components: {},
  data() {
    return {
      images: [
        "products/1.jpg",
        "products/2.jpg",
        "products/3.jpg",
        "products/4.jpg",
        "products/5.jpg",
        "products/6.jpg",
        "products/7.jpg",
        "products/8.jpg",
        "products/9.jpg",
        "products/10.jpg",
        "products/11.jpg",
        "products/12.jpg",
        "products/13.jpg",
        "products/14.jpg",
        "products/15.jpg",
        "products/16.jpg",
        "products/17.jpg",
      ],
    };
  },
};
</script>

<template>
  <div>
    <!-- header section start -->
    <div class="header_section">
      <div class="container-fluid">
        <nav class="navbar navbar-light bg-light justify-content-between">
          <div class="d-flex align-items-center">
            <span class="toggle_icon">
              <a class="logo" href="/">
                <img src="files/logo-r.png" style="width: 100%; height: 5rem" />
              </a>
            </span>
            <ul class="navbar-nav ml-20">
              <li class="nav-item ml-20">
                <a class="nav-link" href="/" style="font-size: 1.5rem;">Home</a>
              </li>
            </ul>
          </div>
          <form class="form-inline ml-auto">
            <div class="login_text">
              <ul></ul>
            </div>
          </form>
        </nav>
      </div>
    </div>
    <!-- header section end -->
    <!-- product section start -->
    <div class="product_section layout_padding">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <h1
              class=""
              style="
                font-family: 'Great Vibes', cursive;
                width: 100%;
                margin: 0 auto;
                font-size: 80px;
                color: #000;
                line-height: 90px;
              "
            >
              Our Products
            </h1>
            <p class="product_text">
              Discover our exclusive range of beauty products crafted to enhance
              your natural allure. Explore, indulge, and transform your look.
            </p>
          </div>
        </div>
        <div class="product_section_2 layout_padding">
          <div class="row">
            <div
              v-for="(image, index) in images"
              :key="index"
              class="col-lg-3 col-sm-6"
            >
              <div class="product_box">
                <img
                  :src="image"
                  class=""
                  style="width: 100%; height: 20rem; border-radius: 0.7rem;"
                />
                <div class="btn_main" style="height: 5rem">
                  <div class="buy_bt">
                    <a
                      href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services"
                      target="_blank"
                    >
                      <img
                        src="files/w.png"
                        alt="WhatsApp"
                        style="width: 3.5rem; height: 3.5rem"
                      />
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- <div class="seemore_bt">
            <a href="" target="_blank">Load More...</a>
          </div> -->
        </div>
      </div>
    </div>
    <!-- product section end -->
    <!-- footer section start -->
    <div class="footer_section layout_padding">
      <div class="container">
        <div class="contact_section_2">
          <div class="row">
            <div class="col-sm-4">
              <h3 class="address_text">Contact Us</h3>
              <div class="address_bt">
                <ul>
                
                  <li>
                    <a href="#">
                      <i class="fa fa-phone" aria-hidden="true"></i
                      ><span class="padding_left10"
                        >Call : +237651269879</span
                      >
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <i class="fa fa-envelope" aria-hidden="true"></i
                      ><span class="padding_left10"
                        >Email : noela@gmail.com</span
                      >
                    </a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-sm-4">
              <div class="text-center">
                <a href="/" class="address_text">
                  <img
                    src="files/logo.png"
                    style="width: 100%; height: 5rem; border-radius: 5px"
                  />
                </a>
              </div>
              <p class="dummy_text">
                We offer an exquisite selection of wigs designed to enhance your
                natural beauty. Our commitment to quality and customer
                satisfaction ensures that you find the perfect look that
                complements your style and personality.
              </p>
            </div>
            <div class="col-sm-4">
              <h3 class="address_text">Categories</h3>
              <div class="address_bt">
                <ul class="custom-list">
                  <li>
                    <a href="#">
                      <span class="padding_left10">Full Lace</span>
                    </a>
                  </li>
                  <li>
                    <span class="padding_left10">Frontal Lace</span>
                  </li>
                  <li>
                    <a href="#">
                      <span class="padding_left10">Raw Hair</span>
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <span class="padding_left10">Wig Closure</span>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="social_icon">
          <ul>
            <li>
              <a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-instagram" aria-hidden="true"></i></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- footer section end -->
    <!-- copyright section start -->
    <div class="copyright_section">
      <div class="container">
        <p class="copyright_text">
          2024 All Rights Reserved. Design by <span>Engr. Temban Blaise</span>
        </p>
      </div>
    </div>
    <!-- copyright section end -->
  </div>
</template>

<style scoped>
.text-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.product_box {
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  /* padding: 20px; */
  margin-bottom: 30px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product_box:hover {
  transform: translateY(-10px);
  box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
}

.product_box .bursh_text {
  font-size: 18px;
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

.product_box .image_1 {
  max-width: 100%;
  border-radius: 8px;
  margin-bottom: 20px;
}

.btn_main {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.buy_bt img {
  width: 32px;
  height: 32px;
}
</style>