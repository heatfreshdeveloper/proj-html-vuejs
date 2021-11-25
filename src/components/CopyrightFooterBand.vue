<template>
  <div class="container-fluid my-footer-band py-3">
      <div class="d-flex py-2 justify-content-evenly flex-row">
        <div class="d-flex align-items-center">
            <div>Enjoy the low price. We are tracking any intention of piracy.</div>
        </div>
        <div class="d-flex align-items-center">
            <div>
                <div class="d-inline-block">©2020 NEXGEN is Proudly Powered by <span class="codings">Codings</span></div>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "CopyrightFooterBand"
}
</script>

<style>

    .my-footer-band {
        background-color: black;
        color: white;
        font-size: 12px;
    }

    .codings {
        color: #157347;
    }
</style>