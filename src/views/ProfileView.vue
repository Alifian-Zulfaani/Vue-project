<template>
  <section class="vh-100" style="background-color: #f4f5f7">
    <div class="container py-5 h-100">
      <div class="row d-flex justify-content-center align-items-center h-100">
        <div class="col col-lg-8 mb-4 mb-lg-0">
          <div class="card mb-3" style="border-radius: 0.5rem">
            <div class="row g-0">
              <div
                class="col-md-4 gradient-custom text-center text-white"
                style="
                  border-top-left-radius: 0.5rem;
                  border-bottom-left-radius: 0.5rem;
                "
              >
                <img
                  src="../assets/alep.png"
                  alt="Avatar"
                  class="icon img-fluid"
                  style="width: 80px"
                />
                <h5>Alifian Zulfaani</h5>
                <p>Fullstack Developer</p>
                <i class="far fa-edit mb-5">o_o</i>
              </div>
              <div class="col-md-8">
                <div class="card-body p-4">
                  <h6 class="text-uppercase">Information</h6>
                  <hr class="mt-0 mb-4" />
                  <!-- Horizontal Line -->
                  <div class="row pt-1">
                    <div class="col-6 mb-3">
                      <h6>Email</h6>
                      <p class="text-muted">inaafilakoko27@gmail.com</p>
                    </div>
                    <div class="col-6 mb-3">
                      <h6>Phone</h6>
                      <p class="text-muted">+62 857 4063 6055</p>
                    </div>
                  </div>
                  <h6 class="text-uppercase">Projects</h6>
                  <hr class="mt-0 mb-4" />
                  <div class="row pt-1">
                    <div class="col-6 mb-3">
                      <h6>Recent</h6>
                      <p class="text-muted">E-Commerce with Laravel</p>
                    </div>
                    <div class="col-6 mb-3">
                      <h6>Most Viewed</h6>
                      <p class="text-muted">Classification of Eye Disease</p>
                    </div>
                  </div>
                  <div class="d-flex justify-content-start">
                    <a href="#"><i class="fab fa-facebook-f fa-lg me-3"></i></a>
                    <a href="#"><i class="fab fa-twitter fa-lg me-3"></i></a>
                    <a href="#"><i class="fab fa-instagram fa-lg"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "ProfileView",
  components: {},
};
</script>

<style scoped>
.icon {
  margin-top: 40px;
  margin-bottom: 20px;
  border-radius: 200%;
}

.gradient-custom {
  /* fallback for old browsers */
  background: #f6d365;

  /* Chrome 10-25, Safari 5.1-6 */
  background: -webkit-linear-gradient(
    to right bottom,
    rgb(44, 117, 89),
    rgb(71, 214, 150)
  );

  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background: linear-gradient(
    to right bottom,
    rgb(44, 117, 89),
    rgb(71, 214, 150)
  );
}
</style>
// style scope hanya berdampak pada file tersebut
