<template>
  <!-- Section "Footer"-->
  <footer class="text-center text-lg-start bg-light text-muted">
    <div
      class="d-flex justify-content-center justify-content-lg-between p-4"
    ></div>

    <!-- Section: Links  -->
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <img class="footer-logo" src="../assets/logo.png" alt="img" />
            <p class="footer-text">
              There are many variations of passages of Lorem Ipsum available,
              but the majority have suffered alteration.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4 footer-contents">
            <!-- Links -->
            <h6 class="fw-bold mb-4">Quick Link</h6>
            <p>
              <a href="#!" class="text-reset">Home</a>
            </p>
            <p>
              <a href="#!" class="text-reset">About</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Service</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Portfolio</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Blog</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4 footer-contents">
            <!-- Links -->
            <h6 class="fw-bold mb-4">About Me</h6>
            <p>
              <a href="#!" class="text-reset">Services Policy</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Terms & Condition</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Online Agreement</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Privacy Policy</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Copyright Issue</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
            <!-- Links -->
            <h6 class="fw-bold mb-4 news-letter">NewsLetter</h6>
            <div class="d-flex justify-content-start">
              <b-form-input v-model="text" placeholder="Email Address">
              </b-form-input>
              <b-button squared variant="info">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-cursor-fill"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M14.082 2.182a.5.5 0 0 1 .103.557L8.528 15.467a.5.5 0 0 1-.917-.007L5.57 10.694.803 8.652a.5.5 0 0 1-.006-.916l12.728-5.657a.5.5 0 0 1 .556.103z"
                  />
                </svg>
              </b-button>
            </div>
          </div>
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="copy-right p-4 border-top d-flex justify-content-around">
      <!-- Left -->
      <!-- When it wraps, I keep only  essential information like payment method.-->
      <div class="d-none d-md-flex">
        Copyright &copy; Raw Graphics All rights reserved.
      </div>
      <!-- Left -->
      <!-- Right -->
      <div class="d-flex">
        <p>Payment Method:</p>
        <img class="payment-logo" src="../assets/visa.svg" alt="img" />
        <img class="payment-logo" src="../assets/mastercard.svg" alt="img" />
        <img class="payment-logo" src="../assets/skrill.svg" alt="img" />
      </div>
      <!-- Right -->
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->
</template>

<script scope>
export default {
  name: "FooterMain",
};
</script>

<style scoped>
.footer-logo {
  margin: -1rem 0rem 2rem -2rem;
}
.footer-text {
  font-family: "PT Sans";
  color: rgba(112, 112, 112, 255);
  text-align: left;
  padding-left: 2rem;
}
.footer-contents h6 {
  font-family: "Roboto Slab", serif;
  font-weight: 600;
  color: rgba(50, 50, 50, 255);
}
.footer-contents p,
.copy-right {
  font-size: 14px;
  font-family: "PT Sans";
  color: rgba(112, 112, 112, 255);
}
.copy-right {
  font-size: 15px;
  text-align: left;
}
.news-letter {
  font-family: "Roboto Slab", serif;
  font-weight: 600;
  color: rgba(50, 50, 50, 255);
  text-align: left;
}
.payment-logo {
  width: 26px;
  height: 22px;
  border: 1px solid rgb(212, 209, 209);
  margin-left: 10px;
}
</style>
