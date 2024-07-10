<script>
export default {
  name: "Home",
  components: {},
};
</script>
<template>
  <div>
    <!-- header section start -->
    <div class="header_section">
      <div class="container-fluid">
        <nav class="navbar navbar-light bg-light justify-content-between">
          <span class="toggle_icon">
            <a class="logo" href="/"
              ><img src="files/logo-r.png" style="width: 100%; height: 5rem"
            /></a>
          </span>
          <form class="form-inline">
            <div class="login_text">
              <ul></ul>
            </div>
          </form>
        </nav>
      </div>
    </div>
    <!-- header section end -->
    <!-- banner section start -->
    <div class="banner_section layout_padding">
      <div
        id="carouselExampleIndicators"
        class="carousel slide"
        data-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="container">
              <div class="row">
                <div class="col-sm-8">
                  <h1 class="banner_taital">Luxurious <br />Silky Wig</h1>
                  <p class="banner_text">
                    Discover the ultimate in luxury with our silky wig, crafted
                    from the finest materials to provide a natural look and
                    feel. Perfect for any occasion, this wig offers unparalleled
                    comfort and style, allowing you to transform your appearance
                    effortlessly. Whether you're attending a formal event or
                    simply want to elevate your everyday look, our silky wig is
                    the ideal choice for those who demand the best.
                  </p>

                </div>
                <div class="col-sm-4">
                  <div
                    class="banner_img"
                    style="width: 100%; height: 130%; z-index: 100"
                  >
                    <img src="files/w2.png" style="height: 28.7rem" />
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="container">
              <div class="row">
                <div class="col-sm-8">
                  <h1 class="banner_taital">Stylish <br />Wave Wig</h1>
                  <p class="banner_text">
                    Achieve the perfect wave with our stylish wig, featuring a
                    natural wave pattern that effortlessly enhances your look.
                    This wig is ideal for those who want a versatile hairstyle
                    that can be dressed up or down, making it suitable for any
                    occasion. With its lightweight design and breathable
                    construction, our wave wig provides all-day comfort while
                    maintaining a flawless appearance. Embrace the beauty of
                    effortless waves with this must-have addition to your
                    collection.
                  </p>
                  <div class="read_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank"
                      >Contact Seller</a
                    >
                  </div>
                </div>
                <div class="col-sm-4">
                  <div
                    class="banner_img"
                    style="
                      width: 100%;
                      height: 100%;
                      z-index: 100;
                      margin-left: 1rem;
                    "
                  >
                    <img src="files/w1.png" style="height: 28.7rem" />
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="container">
              <div class="row">
                <div class="col-sm-8">
                  <h1 class="banner_taital">Elegant <br />Curly Wig</h1>
                  <p class="banner_text">
                    Elevate your style with our elegant curly wig, designed to
                    enhance your natural beauty with its voluminous curls and
                    realistic texture. This wig is perfect for adding a touch of
                    sophistication to any outfit, whether you're heading to a
                    special event or simply want to make a statement. With its
                    secure fit and easy maintenance, our curly wig ensures you
                    look your best with minimal effort, giving you the
                    confidence to shine.
                  </p>
                  <div class="read_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank"
                      >Contact Seller</a
                    >
                  </div>
                </div>
                <div class="col-sm-4">
                  <div
                    class="banner_img"
                    style="
                      width: 100%;
                      height: 100%;
                      z-index: 100;
                      margin-left: 3rem;
                    "
                  >
                    <img src="files/c4.png" style="height: 28.7rem" />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <a style="width: 8.5%;"
          class="carousel-control-prev"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleIndicators"
          role="button"
          data-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>

    <!-- banner section end -->
    <!-- product section start -->
    <div class="product_section layout_padding">
      <div class="container" >
        <div class="row">
          <div class="col-sm-12" >
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
            <div class="col-lg-3 col-sm-6" >
              <div class="product_box" >
                <h4
                  class="bursh_text"
                  style="
                    font-family: 'Great Vibes', cursive;
                    width: 100%;
                    margin: 1rem 0 auto auto;
                    font-size: 40px;
                    color: #000;
                    line-height: 50px;
                  "
                >
                  Frontal Lace Wig
                </h4>
                <!-- <p class="small_text">Elegant and natural-looking wig with a lace front.</p>
            <p class="lorem_text" style="margin-left: 5px; margin-right: 5px;"> 
              random text
            </p> -->
                <img
                  src="files/frontal.png"
                  class=""
                  style="width: 100%; height: 20rem"
                />
                <div class="btn_main" style="height: 5rem">
                  <div class="buy_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank">
                      <img
                        src="files/w.png"
                        alt="WhatsApp"
                        style="width: 3.5rem; height: 3.5rem"
                      />
                    </a>
                  </div>
                  <!-- <h3 class="price_text" style="width: 16rem">
                    Price: 150,000 xaf
                  </h3> -->
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-sm-6">
              <div class="product_box">
                <h4
                  class="bursh_text"
                  style="
                    font-family: 'Great Vibes', cursive;
                    width: 100%;
                    margin: 1rem 0 auto auto;
                    font-size: 40px;
                    color: #000;
                    line-height: 50px;
                  "
                >
                  Full Lace Wig
                </h4>
                <!-- <p class="small_text">Full coverage lace wig for a seamless look.</p>
            <p class="lorem_text" style="margin-left: 5px; margin-right: 5px;"> 
              random text
            </p> -->
                <img
                  src="files/full.png"
                  class=""
                  style="width: 100%; height: 20rem"
                />
                <div class="btn_main" style="height: 5rem">
                  <div class="buy_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank">
                      <img
                        src="files/w.png"
                        alt="WhatsApp"
                        style="width: 3.5rem; height: 3.5rem"
                      />
                    </a>
                  </div>
                  <!-- <h3 class="price_text" style="width: 16rem">
                    Price: 210,000 xaf
                  </h3> -->
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-sm-6">
              <div class="product_box">
                <h4
                  class="bursh_text"
                  style="
                    font-family: 'Great Vibes', cursive;
                    width: 100%;
                    margin: 1rem 0 auto auto;
                    font-size: 40px;
                    color: #000;
                    line-height: 50px;
                  "
                >
                  Wig Closure
                </h4>
                <!-- <p class="small_text">Perfect closure for a natural finish.</p>
            <p class="lorem_text" style="margin-left: 5px; margin-right: 5px;"> 
              random text
            </p> -->
                <img
                  src="files/closure.png"
                  class=""
                  style="width: 100%; height: 20rem"
                />
                <div class="btn_main" style="height: 5rem">
                  <div class="buy_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank">
                      <img
                        src="files/w.png"
                        alt="WhatsApp"
                        style="width: 3.5rem; height: 3.5rem"
                      />
                    </a>
                  </div>
                  <!-- <h3 class="price_text" style="width: 16rem">
                    Price: 250,000 xaf
                  </h3> -->
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-sm-6">
              <div class="product_box">
                <h4
                  class="bursh_text"
                  style="
                    font-family: 'Great Vibes', cursive;
                    width: 100%;
                    margin: 1rem 0 auto auto;
                    font-size: 40px;
                    color: #000;
                    line-height: 50px;
                  "
                >
                  Wig Installation
                </h4>
                <!-- <p class="small_text">Professional wig installation services.</p>
            <p class="lorem_text" style="margin-left: 5px; margin-right: 5px;"> 
              random text
            </p> -->
                <img
                  src="files/installation.png"
                  class=""
                  style="width: 100%; height: 20rem"
                />
                <div class="btn_main" style="height: 5rem">
                  <div class="buy_bt">
                    <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank">
                      <img
                        src="files/w.png"
                        alt="WhatsApp"
                        style="width: 3.5rem; height: 3.5rem"
                      />
                    </a>
                  </div>
                  <!-- <h3 class="price_text" style="width: 16rem">
                    Price: 50,000 xaf
                  </h3> -->
                </div>
              </div>
            </div>
          </div>
          <div class="seemore_bt">
            <a href="/Projects" target="_blank">See More</a>
          </div>
        </div>
      </div>
    </div>
    <!-- product section end -->
    <!-- about section start -->
    <div class="about_section layout_padding">
      <div class="container">
        <div class="about_section_main">
          <div class="row">
            <div class="col-md-7">
              <div class="about_taital_main">
                <h1 class="about_taital">About Us</h1>
                <p class="about_text">
                  Welcome to our Wig Store, your premier destination for
                  high-quality wigs that cater to a variety of styles and
                  preferences. We ensure offering a diverse selection of wigs
                  that are designed to help you look and feel your best, no
                  matter the occasion.
                  <br />
                  Our journey began with a simple mission: to provide
                  individuals with beautiful, natural-looking wigs that enhance
                  their confidence and style. We understand that a wig is more
                  than just a fashion accessory – it’s a way to express your
                  unique personality and beauty. That's why we source our wigs
                  from the most reputable manufacturers, ensuring that each
                  piece is crafted with the highest standards of quality and
                  care.
                </p>
                <p class="about_text">
                  We are dedicated to providing exceptional customer service and
                  a personalized shopping experience. Our knowledgeable and
                  friendly staff are here to assist you in finding the perfect
                  wig that suits your individual needs and style. Whether you
                  are new to wearing wigs or a seasoned wig enthusiast, we are
                  here to support you every step of the way. Thank you for
                  choosing our Wig Store. We are excited to help you discover
                  the perfect wig that enhances your natural beauty and boosts
                  your confidence.
                </p>
              </div>
              <div class="readmore_bt">
                <a href="https://wa.me/+237651269879?text=I%20am%20interested%20in%20your%20wig%20services" target="_blank"
                  >Contact us</a
                >
              </div>
            </div>
            <div class="col-md-5">
              <div
                id="aboutCarousel"
                class="carousel slide"
                data-ride="carousel"
              >
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img
                      src="files/c3.png"
                      class="d-block w-100"
                      style="width: 90%; height: 32rem"
                    />
                  </div>
                  <div class="carousel-item">
                    <img
                      src="files/p1.png"
                      class="d-block w-100"
                      style="width: 90%; height: 32rem"
                    />
                  </div>
                  <div class="carousel-item">
                    <img
                      src="files/p2.png"
                      class="d-block w-100"
                      style="width: 90%; height: 32rem"
                    />
                  </div>
                </div>
                <a
                  class="carousel-control-prev"
                  href="#aboutCarousel"
                  role="button"
                  data-slide="prev"
                >
                  <span
                    class="carousel-control-prev-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only">Previous</span>
                </a>
                <a
                  class="carousel-control-next"
                  href="#aboutCarousel"
                  role="button"
                  data-slide="next"
                >
                  <span
                    class="carousel-control-next-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="sr-only">Next</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- about section end -->
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
                      <i class="fa fa-map-marker" aria-hidden="true"></i
                      ><span class="padding_left10">Address : Loram Ipusm</span>
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <i class="fa fa-phone" aria-hidden="true"></i
                      ><span class="padding_left10"
                        >Call : +237-674-111-881</span
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