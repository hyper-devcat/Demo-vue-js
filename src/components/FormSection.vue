<template>
  <!-- Section "We give solution" -->
  <section id="form">
    <div class="form container">
      <b-container class="bv-example-row">
        <b-row>
          <b-col col lg="5" md="12" class="left-form"></b-col>
          <b-col col lg="7" md="12" class="right-form">
            <h6>We give solution</h6>
            <p><span class="for-border">&emsp;&emsp;&emsp;</span></p>
            <h3>
              If you have any questions <br />
              please don't hesitate to contact us
            </h3>
            <div class="row">
              <!-- Form -->
              <b-col cols="6">
                <b-form-input
                  id="input-default"
                  placeholder="Name"
                ></b-form-input>
              </b-col>
              <b-col cols="6">
                <b-form-input
                  id="input-default"
                  placeholder="Email Adresss"
                ></b-form-input>
              </b-col>
              <b-col cols="12">
                <div class="msg-area">
                  <b-form-textarea
                    id="textarea-rows"
                    placeholder="Message"
                    rows="6"
                  >
                  </b-form-textarea>
                </div>
              </b-col>
              <!-- End of Form -->
            </div>
            <b-button class="btn-msg"> Send Message </b-button>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </section>
</template>

<script>
export default {
  name: "FormSection",
};
</script>

<style scoped>
#form .container {
  min-height: 50vh;
  max-width: 100vw;
  flex-direction: row;
  background-color: rgba(146, 146, 146, 255);
  padding: 0px 0px;
}
#form .row {
  margin: 0px 0px;
}
/* Form CSS */
#form .right-form {
  background-color: rgba(255, 255, 255, 255);
  min-height: 60vh;
  padding-right: 10rem;
}
.right-form h6 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-size: 15px;
  margin-top: 2rem;
  padding-left: 1rem;
}
.right-form .for-border {
  color: rgba(0, 184, 148, 255);
  margin-left: 1rem;
  font-weight: 800;
  border-top: solid;
  border-width: 2px;
}
.right-form h3 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 23px;
  text-align: left;
  margin: 0 0 5rem 1rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
#textarea-rows {
  margin: 2rem 1rem 0 0;
}
#input-default,
#textarea-rows {
  font-family: "PT Sans";
}
/*  Button CSS */
.btn-msg {
  display: inline-block;
  padding: 10px 20px;
  margin: auto;
  color: rgba(254, 254, 254, 255);
  background-color: rgba(0, 184, 148, 255);
  font-family: "PT Sans";
  font-size: 1rem;
  margin-top: 2rem;
  transition: 0.3s ease;
  text-decoration: none;
  margin: 1rem 0 1rem 1rem;
  border: none;
}
.btn-msg:hover {
  color: white;
  background-color: mediumaquamarine;
}
/*  End Button CSS */
/* "We give solution" responsive */
@media only screen and (max-width: 800px) {
  .left-form {
    display: none;
  }
}
</style>
