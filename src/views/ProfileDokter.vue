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
        </div>

            <div class="head">
              <!-- <h1>HAI</h1> -->
                <div class="post-entry-1 h-200 person-1" style="margin-left: 0px">
                    <!-- <img src="images/person_3.jpg" class="w3-round-xxlarge" alt="Norway" style="width:15%"> -->
                        <!-- <table style="margin: 0px;"> -->
                        <tbody>
                            <tr>
                            <td rowspan="2"><img style="width: 200px; height: 200px; margin-left: 370px; margin-top: 8px"
                                alt="Kang Logo"
                                src="images/person_3.jpg">
                            </td>
                                <td style>
                                    <br><br>
                                    <h1><span class="tab">dr James Doe</span></h1>
                                    <p style="color: #888888; font-size: 22px; margin-left: -25px">Kardiologi Klinik</p>
                                    <!-- <hr style="width:50%;text-align:left;margin-left70;height:5px"> -->
                                    <hr style="width:60%;text-align:left;height:2px;border-width:0;background-color:#888888">
                                    <h2 style="margin-left: -40px">4.4</h2>
                                </td>
                            </tr>
                        </tbody>
                        <!-- </table> -->
                </div>
            </div><br><br>

        <div class="container">
                <h2 style="float: left"> Profil Dokter </h2>
                <p align="left" style="margin-top: 70px; margin-bottom: 60px">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Volutpat consequat vulputate mi platea interdum ut. Urna, mus consequat, donec at ut sed. Ullamcorper nunc sed volutpat donec arcu turpis. Sollicitudin risus nec, velit purus nunc purus metus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Volutpat consequat vulputate mi platea interdum ut. Urna, mus consequat, donec at ut sed. Ullamcorper nunc sed volutpat donec arcu turpis. Sollicitudin risus nec, velit purus nunc purus metus.</p>
                <h2 style="float: left"> Lokasi dan Jadwal Praktik </h2>
                <!-- <img src="../assets/rs.jpeg" class="img-thumbnail" alt="Cinque Terre" width="304" height="236">  -->
                    <tbody>
                        <tr>
                        <td rowspan="2"><img style="width: 250px; height: 250px; margin-left: -490px; margin-top: 90px"
                            alt="Kang Logo"
                            src="../assets/rs.jpeg">
                        </td>
                            <td style>
                                <!-- <h1><span class="tab">dr James Doe</span></h1> -->
                                <h5 style="margin-left: -40px; color: #2757D2; margin-top: 30px">RSU Pindad (Kiaracondong, Bandung)</h5>
                                <!-- <h7 style="margin-left: -40px; margin-bottom: 150px; color: #2757D2">RSU Pindad (Kiaracondong, Bandung)</h7> -->
                                <p style="margin-left: -230px; margin-top: 20px; color: #EA2931">Mulai dari Rp 50.000</p>

                                <div class="dropdown" style="margin-left: -130px; margin-bottom: 10px">
                                  <router-link  to='IsiDataPemesan' class="nav-link"><button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">Jumat, 22 Oktober 2020
                                  <span class="caret"></span></button></router-link>
                                  <ul class="dropdown-menu">
                                    <li><a href="#">HTML</a></li>
                                    <li><a href="#">CSS</a></li>
                                    <li><a href="#">JavaScript</a></li>
                                  </ul>
                                </div>

                                <div class="dropdown" style="margin-left: -130px">
                                  <button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">Sabtu, 23 Oktober 2020
                                  <span class="caret"></span></button>
                                  <ul class="dropdown-menu">
                                    <li><a href="#">HTML</a></li>
                                    <li><a href="#">CSS</a></li>
                                    <li><a href="#">JavaScript</a></li>
                                  </ul>
                                </div>
                                

                            </td>
                        </tr>
                    </tbody>

                     <p align="left" style="margin-top: 70px; color:#2757D2">Jadwal Praktik</p>

                      <div class="row">
                        <div class="col-sm-3" align="left">Hari</div>
                        <div class="col-sm-3">Jadwal</div>
                        <div class="col-sm-3">Hari</div>
                        <div class="col-sm-3" align="right">Jadwal</div>
                      </div>

                      <div class="row">
                        <hr style="margin-left: 5px; width:42%; height:2px; border-width:0; background-color:#888888">
                        <hr style="margin-right: 0px; width:42%; height:2px; border-width:0; background-color:#888888">
                        <div class="col-sm-3" align="left">Senin</div>
                        <div class="col-sm-3">09:00 - 11:00</div>
                        <div class="col-sm-3">Rabu</div>
                        <div class="col-sm-3" align="right">09:00 - 11:00</div>
                      </div>

                      <div class="row">
                        <div class="col-sm-5" style="margin-left: 12px;" align="right">11:00 - 13:00</div>
                        <div class="col-sm-5" style="margin-left: 177px;" align="right">11:00 - 13:00</div>
                      </div>

                      <div class="row">
                        <div class="col-sm-5" style="margin-left: 12px;" align="right">13:00 - 15:00</div>
                        <div class="col-sm-5" style="margin-left: 177px;" align="right">13:00 - 15:00</div>
                      </div>
                      <br>

                      <div class="row">
                        <div class="col-sm-3" align="left">Selasa</div>
                        <div class="col-sm-3">09:00 - 11:00</div>
                        <div class="col-sm-3">Kamis</div>
                        <div class="col-sm-3" align="right">09:00 - 11:00</div>
                      </div>

                      <div class="row">
                        <div class="col-sm-5" style="margin-left: 12px;" align="right">11:00 - 13:00</div>
                        <div class="col-sm-5" style="margin-left: 177px;" align="right">11:00 - 13:00</div>
                      </div>

                       <div class="row">
                        <div class="col-sm-5" style="margin-left: 12px;" align="right">13:00 - 15:00</div>
                        <div class="col-sm-5" style="margin-left: 177px;" align="right">13:00 - 15:00</div>
                      </div>
                    
          </div>

        <!-- <div class="container">
          <h2 style="float: left"> Pengalaman Praktik </h2>

         
            <p>Dokter Jantung Umum - RS Awal Bros Bekasi</p>
         

          <h2 style="float: left"> Pengalaman Praktik </h2>  

          <div class="box">
            <p>Dokter Jantung Umum - RS Awal Bros Bekasi</p>
          </div> 
        </div> -->
                 

      </header>
    </div>
</template>

<style>
.head{
    background-color: #f2f2f2;
    margin-top: 60px;
    margin-left: -20px;
    margin-right: -20px;
    height: 280px;

}
.box{
  background-color: #f2f2f2;
  height: 40px;
  width: 60%;
  margin-left: 150px;
}

</style>