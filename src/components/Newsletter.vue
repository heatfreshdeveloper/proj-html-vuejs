<template>
  <div class="newsletter-hero d-flex align-items-center">
      <div class="newsletter-container">
          <div class="row row-cols-2">
              <div class="col">
                    <div class="my-titles-newsletter">
                        <p>NEWSLETTER</p>
                    </div>
                    <div class="main-title-newsletter">
                        <h1><span class="px-3">Know</span> First</h1>
                    </div>
                    <div class="newsletter-description">
                        <p>Follow closely and receive content about 
                            our company and the news of the current market.
                        </p>
                    </div>
              </div>
              <div class="col">
                  <div class="form-newsletter">
                      <input type="text" class="form-control newsletter-name my-3" placeholder="Name">
                      <input type="text" class="form-control newsletter-email" placeholder="Email">
                      <button type="button" class="btn btn-success my-3">SUBSCRIBE</button>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Newsletter",
}
</script>

<style>
    .newsletter-hero {
        background-image: url(../assets/bg-1.jpg);
        min-height: 400px;
        background-position: 40% 50%;
    }

    .newsletter-container {
        padding-left: 350px;
        padding-right: 350px;
        color: white;
    }

    .my-titles-newsletter {
        color: #157347;
    }

    .main-title-newsletter {
        color: rgb(163, 153, 153);
        z-index: 10;
        margin-bottom: 20px;
        font-family: 'Mochiy Pop P One', sans-serif;
        font-family: 'Roboto', sans-serif;
    }

    .main-title-newsletter span {
        background-color: #157347;
        opacity: 0.5;
        color: white;
        border-radius: 5px;
        padding-bottom: 5px;
    }

    .newsletter-name {
        opacity: 0.5;
    }

    .newsletter-email {
        opacity: 0.5;
    }
</style>