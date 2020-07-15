<template>
<header class="site-navbar site-navbar-target" role="banner">
        <div class="container">
          <div class="row align-items-center position-relative">
            <!-- <div class="col"> -->
              <div class="site-logo">
                <img alt="Vue logo" src="../assets/Logo_Medtek.png" width="150px">
              </div>
          </div>
        </div>

    <div class="container" style="position: relative; z-index: 1; max-width: 300px; margin: 0 auto;">
        <div class="login-page" style="width: 360px; padding: 8% 0 0; margin: auto;">
          <div class="form" style="z-index: 1; background: #FFFFFF; width: 500px; margin-left: -90px; padding: 50px; text-align: center;box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24)">
            <!-- <form class="register-form">
              <input type="text" placeholder="name"/>
              <input type="password" placeholder="password"/>
              <input type="text" placeholder="email address"/>
              <button>create</button>
              <p class="message">Already registered? <a href="#">Sign In</a></p>
            </form> -->
            <form class="login-form">
              <h2>Isi Data Pemesan</h2>
              <p>Silahkan isi data pemesan untuk menerima informasi untuk buat janji</p>
              <input type="text" placeholder="No Handphone"/>
              <input type="email" placeholder="Email"/>
              <input type="text" placeholder="Nama Lengkap"/>
              <router-link  to='IsiDataPemesan2' class="nav-link"><button>Selanjutnya</button></router-link>
              
            </form>
          </div>
        </div>
    </div>
</header>
</template>

<style>
.form input {
  font-family: "Roboto", sans-serif;
  outline: 0;
  background: #f2f2f2;
  width: 100%;
  border: 0;
  margin: 0 0 15px;
  padding: 15px;
  box-sizing: border-box;
  font-size: 14px;
}
.form button {
  font-family: "Roboto", sans-serif;
  text-transform: uppercase;
  outline: 0;
  background: #2F80ED;
  width: 100%;
  border: 0;
  padding: 15px;
  color: #FFFFFF;
  font-size: 14px;
  -webkit-transition: all 0.3 ease;
  transition: all 0.3 ease;
  cursor: pointer;
}
.form button:hover,.form button:active,.form button:focus {
  background: #2F80ED;
}
.form .message {
  margin: 15px 0 0;
  color: #b3b3b3;
  font-size: 12px;
}
.form .message a {
  color: #2F80ED;
  text-decoration: none;
}
.form .register-form {
  display: none;
}
</style>