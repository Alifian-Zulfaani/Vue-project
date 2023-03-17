<template>
  <section class="login d-flex">
    <div class="login-left w-50 h-100">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-6">
          <div class="header">
            <h2>Welcome</h2>
            <p>Selamat datang di web kesayangan saya</p>
          </div>

          <div class="login-form">
            <label for="email" class="form-label">Email</label>
            <input
              type="email"
              class="form-control"
              id="email"
              placeholder="Masukkan email"
            />
            <label for="password" class="form-label">Password</label>
            <input
              type="password"
              class="form-control"
              id="password"
              placeholder="Masukkan password"
            />
            <a href="#" class="text-decoration-none text-center"
              >Forgot password</a
            >

            <button class="signin">Sign In</button>
            <button class="signin-google">
              <img src="../assets/icon-google.png" alt="" />
              Sign In With Google
            </button>

            <div class="text-center">
              <span class="d-inline"
                >Don’t have an account?
                <a href="#" class="signup d-inline text-decoration-none"
                  >Sign up for free</a
                ></span
              >
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="login-right w-50 h-100">
      <div
        id="carouselExampleFade"
        class="carousel slide carousel-fade"
        data-bs-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../assets/1.png" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/2.png" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="../assets/3.png" class="d-block w-100" alt="..." />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExampleFade"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExampleFade"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </section>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap/js/dist/carousel";

export default {
  name: "HomeView",
  components: {},
};
</script>

<style scoped>
.login {
  height: 100vh;
  overflow: hidden; /* Hide Scrollbar */
}

.header h1 {
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 48px;
  color: #000000;
}

.header p {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 21px;
  color: #737373;
  margin-bottom: 20px;
}

.login-form label {
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  color: #000000;
  margin-top: 20px;
}

.login-form input {
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  color: #737373;
}

.login-form a {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 21px;
  color: #737373;
  margin: 20px 0;
  display: block;
}

.login-form .signin {
  width: 100%;
  height: 42px;
  background: #000000;
  border-radius: 8px;
  color: #fff;
  border: none;
}

.login-form .signin-google {
  width: 100%;
  height: 42px;
  background: #ffffff;
  border: 1px solid #bcbcbc;
  border-radius: 8px;
  margin: 10px 0 20px 0;
}

.login-form span {
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 21px;
  color: #737373;
}

.login-form span a {
  font-weight: 600;
}
</style>
