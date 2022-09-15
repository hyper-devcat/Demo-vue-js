<template>
  <!-- Section "Client Feedback" -->
  <section id="client">
    <div class="client container">
      <div class="client-top">
        <h3>Client Feedback</h3>
      </div>
      <!-- Card Feedback -->
      <div class="client-bottom">
        <b-container class="bv-example-row">
          <div class="row">
            <b-col
              v-for="(card, i) in cards"
              :key="i"
              sm="12"
              md="6"
              lg="6"
              xl="6"
              class="client-col"
            >
              <b-card>
                <img src="../assets/_.png" alt="img" class="client-logo" />
                <b-card-text class="feedback-text">
                  {{ card.feedback }}
                </b-card-text>
                <b-row class="client-sign">
                  <b-col cols="8" class="d-flex">
                    <img
                      src="../assets/feedback.png"
                      alt="img"
                      class="feedback-avatar"
                    />
                    <div class="client-font">
                      <span class="name-font"> {{ card.name }}</span>
                      <br />
                      <span> {{ card.title }}</span>
                    </div>
                  </b-col>
                  <b-col class="signature" cols="4">
                    {{ card.name }}
                  </b-col>
                </b-row>
              </b-card>
            </b-col>
          </div>
        </b-container>
      </div>
      <!-- End of Card Feedback -->
    </div>
  </section>
</template>

<script>
export default {
  name: "ClientSection",
  data() {
    return {
      cards: [
        {
          feedback:
            "It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable.",
          name: "Conrad Hegarty",
          title: "CEO, Codeddas",
        },
        {
          feedback:
            "It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable.",
          name: "Patricia Moreno",
          title: "CEO, Codeddas",
        },
      ],
    };
  },
};
</script>

<style scoped>
#client .container {
  min-height: 50vh;
  width: 100%;
  align-items: center;
  background-color: rgba(255, 255, 255, 255);
}
.client-top h3 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 35px;
  text-align: center;
  padding-top: 5rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-skip-ink: none;
  text-decoration-thickness: 5px;
}
.client-bottom {
  display: flex;
  flex-wrap: wrap;
  margin-top: 50px;
}
.client-col {
  margin-bottom: 2rem;
}
#client .card {
  min-height: 35vh;
}
#client .card-body {
  padding: 50px 30px;
}
.client-logo {
  margin-bottom: 2rem;
}
.feedback-text {
  margin-bottom: 2rem;
}
.feedback-avatar {
  width: auto;
  height: 4rem;
}
.name-font {
  font-weight: bold;
}
.client-font {
  font-family: "Roboto Slab", serif;
  font-size: 14px;
  padding-left: 1rem;
}
.signature {
  font-family: "Mistral";
  font-size: 20px;
}
/* Feedback responsive */
@media (width: 1000px) {
  .client-sign {
    flex-direction: column;
  }
}
</style>
