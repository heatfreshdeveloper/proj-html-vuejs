<template>
  <div class="container-fluid my-header-band">
      <div class="d-flex py-2 justify-content-evenly flex-row">
        <div class="d-flex align-items-center">
            <i class="far fa-clock me-2"></i>
            <div>Open Hours: Mon - Sat 9:00 - 18.00</div>
        </div>
        <div class="d-flex align-items-center">
            <div>
                <i class="fas fa-phone-alt d-inline-block me-2"></i>
                <div class="d-inline-block me-3">+1 (305) 1234-5678</div>
            </div>
            <div>
                <i class="far fa-envelope d-inline-block me-2"></i>
                <div class="d-inline-block me-3">hello@example.com</div>
            </div>
            <i class="fab fa-facebook me-2"></i>
            <i class="fab fa-twitter me-2"></i>
            <i class="fab fa-linkedin-in me-2"></i>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "ContactHeaderBand",
}
</script>

<style>
    .my-header-band {
        background-color: #21333E;
        color: white;
        font-size: 15px;
    }

</style>