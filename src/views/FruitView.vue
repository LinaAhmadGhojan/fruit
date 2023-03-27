<template>
  <section class="fruit_section layout_padding">
    <div class="container">
      <div class="heading_container">
        <hr>
        <h2>
          Fresh Fruit
        </h2>
      </div>
    </div>
    <div class="container-fluid">

      <div class="fruit_container">
        <div class="box">
          <img src="../assets/image/f-1.jpg" alt="">
          <div class="link_box">
            <h5>
              Orange
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
        <div class="box">
          <img src="../assets/image/f-2.jpg" alt="">
          <div class="link_box">
            <h5>
              Blueberry
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
        <div class="box">
          <img src="../assets/image/f-3.jpg" alt="">
          <div class="link_box">
            <h5>
              Banana
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
        <div class="box">
          <img src="../assets/image/f-4.jpg" alt="">
          <div class="link_box">
            <h5>
              Apple
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
        <div class="box">
          <img src="../assets/image/f-5.jpg" alt="">
          <div class="link_box">
            <h5>
              Mango
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
        <div class="box">
          <img src="../assets/image/f-6.jpg" alt="">
          <div class="link_box">
            <h5>
              Strawberry
            </h5>
            <a href="">
              Buy Now
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- end fruit section -->


  <!-- info section -->

  <section class="info_section layout_padding">
    <div class="container">
      <div class="info_logo">
        <h2>
          NiNom
        </h2>
      </div>
      <div class="info_contact">
        <div class="row">
          <div class="col-md-4">
            <a href="">
              <img src="../assets/image/location.png" alt="">
              <span>
                Passages of Lorem Ipsum available
              </span>
            </a>
          </div>
          <div class="col-md-4">
            <a href="">
              <img src="../assets/image/call.png" alt="">
              <span>
                Call : +012334567890
              </span>
            </a>
          </div>
          <div class="col-md-4">
            <a href="">
              <img src="../assets/image/mail.png" alt="">
              <span>
                demo@gmail.com
              </span>
            </a>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-8 col-lg-9">
          <div class="info_form">
            <form action="">
              <input type="text" placeholder="Enter your email">
              <button>
                subscribe
              </button>
            </form>
          </div>
        </div>
        <div class="col-md-4 col-lg-3">
          <div class="info_social">
            <div>
              <a href="">
                <img src="../assets/image/facebook-logo-button.png" alt="">
              </a>
            </div>
            <div>
              <a href="">
                <img src="../assets/image/twitter-logo-button.png" alt="">
              </a>
            </div>
            <div>
              <a href="">
                <img src="../assets/image/linkedin.png" alt="">
              </a>
            </div>
            <div>
              <a href="">
                <img src="../assets/image/instagram.png" alt="">
              </a>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<script>

export default {
  data: function()
 { 
  return {
    pagename:"FruitView",
    pagedescription:"This is an help page"
  } ;
},
name:"help"
    
  }


</script>
  <style>
  @media (min-width: 1024px) {
    .help {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .class-help{
      text-align: center;
    }
  }
  </style>
  