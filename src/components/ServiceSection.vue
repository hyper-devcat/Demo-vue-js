<template>
  <!--  Section "My Provide Services" -->
  <section id="services">
    <div class="services container">
      <div class="service-top">
        <h3>My Provide Services</h3>
      </div>
      <div class="service-bottom">
        <b-container class="bv-example-row">
          <div class="row kind-container">
            <b-col
              v-for="(card, i) in cards"
              :key="i"
              sm="12"
              md="6"
              lg="6"
              xl="4"
              class="service-col"
            >
              <b-card>
                <img :src="`${card.icon}`" alt="img" class="service-logo" />
                <h5>{{ card.title }}</h5>
                <b-card-text>
                  There are many variations of passages of Lorem Ipsum
                  available, but the majority have suffered alteration.
                </b-card-text>
              </b-card>
            </b-col>
          </div>
        </b-container>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ServiceSection",
  data() {
    return {
      cards: [
        {
          icon: "/assets/Graphic.png",
          title: "Graphic Design",
        },
        {
          icon: "/assets/SEO.png",
          title: "SEO Marketing",
        },
        {
          icon: "/assets/Data.png",
          title: "Data Analysis",
        },
        {
          icon: "/assets/Digital.png",
          title: "Digital Marketing",
        },
        {
          icon: "/assets/Video.png",
          title: "Video Editing",
        },
        {
          icon: "/assets/Photography.png",
          title: "Photography",
        },
      ],
    };
  },
};
</script>

<style scoped>
#services .container {
  min-height: 40vh;
  width: 100%;
  display: flex;
  align-items: center;
  background-color: rgba(245, 246, 251, 255);
}
/* Card CSS */
.service-top h3 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 35px;
  text-align: center;
  padding-top: 5rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
#services .services {
  flex-direction: column;
  max-width: 100vw;
  min-height: 90vh;
}
#services .service-top {
  max-width: 500px;
  margin: 0 auto;
}
#services .service-bottom {
  display: flex;
  flex-wrap: wrap;
  margin-top: 50px;
}
.service-logo {
  margin-bottom: 2rem;
  align-items: center;
}
h5 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  padding-bottom: 1rem;
}
p {
  font-family: "PT Sans";
  color: rgba(112, 112, 112, 255);
}
.service-col {
  margin-bottom: 1rem;
}
#services .card-body {
  min-width: 15rem;
  min-height: 20rem;
  padding: 3rem;
}
/*  Container of 6 cards CSS */
.kind-container {
  margin-bottom: 5rem;
}
</style>
