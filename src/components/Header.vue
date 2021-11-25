<template>
  <div class="my-header">
      <div class="my-container">
          <nav class="navbar navbar-expand-lg navbar-light">
              <div class="container-fluid">
                <img class="navbar-brand" href="#" src="../assets/image.png"/>
                <ul class="navbar-nav mb-2 mb-lg-0">
                    <li v-for="nav in navList" :key="nav.items" class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">{{ nav.items }}</a>
                    </li>
                </ul>
              </div>
            </nav>
            <div class="consulting-box">
                <div class="my-titles">
                    <p>FUSIONS & ACQUISITIONS</p>
                </div>
                <div class="main-title">
                    <h1>Insurance 
                        <br>Consulting</h1>
                </div>
                <div class="row row-cols-2 gy-3">
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Name">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Email">
                    </div>
                    <div class="col">
                        <input type="text" class="form-control" placeholder="Phone">
                    </div>
                    <div class="col">
                        <div class="accordion-item">
                            <div class="accordion-header">
                                <button class="accordion-button arrow-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                    More info
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="consulting-buttons mt-3">
                    <button type="button" class="btn btn-success mx-2">GET IN TOUCH</button>
                    <button type="button" class="btn btn-outline-success">READ MORE</button>
                </div>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            navList: [
                {items: "HOME"}, 
                {items: "ABOUT"}, 
                {items: "SERVICES"}, 
                {items: "PROCESS"},
                {items: "TEAM"}, 
                {items: "BLOG"}, 
                {items: "GET IN TOUCH"} 
            ],
        }
    }
}
</script>

<style>
    .my-header {
        background-image: url(../assets/bg-6.jpg);
        background-position: 30% 30%;
        min-height: 800px;
        position: relative;
    }

    .my-container {
        padding-left: 280px;
        padding-right: 280px;
    }

    .my-container ul li:nth-child(7) {
        background-color: #157347;
        color: white !important;
        border-radius: 5px;
    }

    .consulting-box {
        position: absolute;
        top: 30%;
        right: 20%;
        max-width: 450px;
    }

    .my-titles {
        color: #157347;
    }

    .arrow-button {
        height: 37px;
    }
</style>