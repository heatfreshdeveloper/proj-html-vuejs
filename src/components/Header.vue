<template>
  <div class="my-header">
      <div class="container">
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
              <div class="container-fluid">
                <img class="navbar-brand" href="#" />
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li v-for="nav in navList" :key="nav.items" class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">{{ nav.items }}</a>
                    </li>
                </ul>
              </div>
            </nav>
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
        
    }
</style>