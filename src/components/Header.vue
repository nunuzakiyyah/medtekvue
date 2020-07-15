<template>
    <div>
        <header class="site-navbar site-navbar-target" role="banner">
        <div class="container">
          <div class="row align-items-center position-relative">
            <!-- <div class="col"> -->
              <div class="site-logo">
                <img alt="Vue logo" src="../assets/Logo_Medtek.png" width="150px">
              </div>
            <!-- </div> -->
            <!-- <div class="col-9 text-right text-lg-left"> -->
              <span class="d-inline-block d-lg-none"><a href="#" class=" site-menu-toggle js-menu-toggle py-5 "><span class="icon-menu h3 text-black"></span></a></span>
              <nav class="site-navigation text-right ml-auto d-none d-lg-block" role="navigation">
                <ul class="site-menu main-menu js-clone-nav ml-auto ">
                  <li class="active"><a href="index.html" class="nav-link">Beranda</a></li>
                  <li class="active"><a href="index.html" class="nav-link">Tanya Dokter</a></li>
                  <li class="active"><a href="index.html" class="nav-link">Cari Dokter</a></li>
                  <li class="active"><a href="index.html" class="nav-link">Login</a></li>
                 
                </ul>
              </nav>
            <!-- </div> -->
          </div>
          <br>
            <div class="container">
              <div class="active-pink-3 active-pink-4 mb-4">
                <i class="glyphicon glyphicon-user form-control-feedback"></i>
                <input class="form-control" type="text" placeholder="Lokasi" aria-label="Search">
                <input class="form-control" type="text" placeholder="Cari Dokter atau Rumah Sakit" aria-label="Search">
              </div>
            </div>
          
        </div>
      </header>
    </div>

    
</template>

<script>
export default {
    name: 'Header'
  }
</script>

<style>
.form-control{
  border-radius: 25px;
  width: 260px;
  float: left;
  margin-right: 10px;
}

</style>