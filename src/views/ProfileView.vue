<template>
  <section>
    <div class="profile d-flex">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="d-flex">
              <div class="flex-shrink-0">
                <img src="../assets/alep.png" class="mr-3 user-pic" />
              </div>
              <div class="flex-grow-1 ms-3 text-start">
                <h5>Alepp - KokoShiWo</h5>
                <p>
                  This is some content from a media component. You can replace
                  this with any content and adjust it as needed.
                </p>
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
.profile {
  margin-top: 20px;
}
.user-pic {
  width: 90px;
  height: 90px;
  border-radius: 200%;
}
</style>
// style scope hanya berdampak pada file tersebut
