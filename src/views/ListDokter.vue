<template>
  <div class="listDokter"> 
    <carousel /> 
    <Header />  
    <!-- <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>  -->
    <div class="site-section bg-light" style="margin-top: 200px">
      <div class="container">
        <div class="row justify-content-center text-center mb-5 section-2-title">
          <div class="col-md-6">
            <!-- <h2 class="mb-4">Meet Our Team</h2> -->
          </div>
        </div>
        <div class="row align-items-stretch">

          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_1.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span> -->
                <h2>dr James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 50.000</p>
                  <button type="button" class="btn btn-primary"><b>Buat Janji</b></button>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_2.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span> -->
                <h2>dr James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 25.000</p>
                  <button type="button" class="btn btn-primary"><b>Buat Janji</b></button>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_3.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span> -->
                <h2>James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 100.000</p>
                  <router-link  to='ProfileDokter' class="nav-link"><button type="button" class="btn btn-primary"><b>Buat Janji</b></button></router-link>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_4.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span> -->
                <h2>James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 100.000</p>
                  <button type="button" class="btn btn-primary"><b>Buat Janji</b></button>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_5.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span>  -->
                <h2>James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 100.000</p>
                  <button type="button" class="btn btn-primary"><b>Buat Janji</b></button>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 mb-5">
            <div class="post-entry-1 h-100 person-1">

              <img src="images/person_1.jpg" alt="Image"
              class="img-fluid">

              <div class="post-entry-1-contents">
                <!-- <span class="meta">Founder</span> -->
                <h2>dr James Doe</h2>
                <p style="color: #B2B1B1">Rehabilitas dan Prevensi</p>
                <p style="color: #B2B1B1">RSU Pindad (Kiaracondong, Bandung)</p>
                <!-- <span class="glyphicon glyphicon-search" aria-hidden="true"></span> -->
                <p style="font-weight: bold">4.4<span class="tab">2.0 km</span></p>
                <p style="color: red">Rp 100.000</p>
                  <button type="button" class="btn btn-primary"><b>Buat Janji</b></button>
              </div>
              <br>
              <button type="button" class="btn btn-primary" style="border-radius: 5px"><b>Selanjutnya >>  </b></button>
            </div>
          </div>
        </div>
    </div>
    </div>
  </div>
  
</template>

<script>

import Header from '@/components/Header.vue'
import carousel from 'vue-owl-carousel';

export default {
    name: 'listDokter',
    components: {
      Header,
      carousel
      // Dokter,
      // Lokasi,
    }
}


</script>

<style>
.site-section{
  margin-top: 0px;
}
.tab{
  display: inline-block;
  margin-left: 40px;;
}
.post-entry-1-contents{
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}


</style>