<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
 
  

    <section class="nav_section" style="margin-top: 19px;">
      <div class="container">
        <div class="custom_nav2">
          <nav class="navbar navbar-expand custom_nav-container ">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
  
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <div class="d-flex  flex-column flex-lg-row align-items-center">
                <ul class="navbar-nav  ">
                  <li class="nav-item active">
                    <a class="nav-link" href="/">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/about">About </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/fruit">Our Fruit </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="/contact">Contact Us</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Login</a>
                  </li>
                </ul>
                <form class="form-inline my-2 my-lg-0 ml-0 ml-lg-4 mb-3 mb-lg-0">
                  <button class="btn  my-2 my-sm-0 nav_search-btn" type="submit"></button>
                </form>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </section>

  <RouterView />
  
</template>
<style lang="scss">
  header{
    background-color: black;
    color: #fff;
    overflow: hidden;

  }
  a{
    text-decoration:none !important;
    color: #fff !important;
  }
  ul{
    padding: 5px;
    float: left;
    width: calc(100% );
    text-align: center;
  }
  li{
    display: inline;
    padding: 20px;
  }
</style>


