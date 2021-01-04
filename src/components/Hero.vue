<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="mt-4 d-none d-md-block">
      <div class="row">
        <div class="col-md-6 align-self-center">
          <h2><strong>Delicious Food Menu, </strong><br />in Your Gadget</h2>
          <p>Ayo segera pilih dan pesan makanan favoritn anda</p>
          <router-link to="/pesan">
            <button class="btn btn-success btn-sm">
              <b-icon-arrow-right></b-icon-arrow-right> Pesan
            </button>
          </router-link>
        </div>
        <div class="col">
          <img
            src="../assets/images/undraw_eating_together_tjhx.svg"
            alt=""
            width="100%"
          />
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="mt-4 d-sm-block d-md-none">
      <div class="row">
        <div class="col-md-6">
          <img
            src="../assets/images/undraw_eating_together_tjhx.svg"
            alt=""
            width="100%"
          />
        </div>
        <div class="col-md-6 align-self-center">
          <h2><strong>Delicious Food Menu, </strong><br />in Your Gadget</h2>
          <p>Ayo segera pilih dan pesan makanan favoritn anda</p>
          <router-link to="/pesan">
            <button class="btn btn-success btn-sm">
              <b-icon-arrow-right></b-icon-arrow-right> Pesan
            </button>
          </router-link>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Hero",
};
</script>