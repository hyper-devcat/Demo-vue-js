<template>
  <!--  Section "Latest Project -->
  <section id="project">
    <div class="project container">
      <div class="project-top">
        <h3>Latest Project</h3>
      </div>
      <div class="project-middle">
        <b-navbar toggleable="lg">
          <b-navbar-brand href="#">
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
              <!-- Right aligned nav items -->
              <b-navbar-nav class="ml-auto">
                <b-navbar-nav>
                  <b-nav-item class="nav-items" href="#">All</b-nav-item>
                  <b-nav-item class="nav-items" href="#"
                    >Graphic Design</b-nav-item
                  >
                  <b-nav-item class="nav-items" href="#"
                    >Web developmet</b-nav-item
                  >
                  <b-nav-item class="nav-items" href="#"
                    >Video Editing</b-nav-item
                  >
                  <b-nav-item class="nav-items" href="#"
                    >Photography</b-nav-item
                  >
                  <b-nav-item class="nav-items" href="#">Others</b-nav-item>
                </b-navbar-nav>
              </b-navbar-nav>
            </b-collapse>
          </b-navbar-brand>
        </b-navbar>
      </div>
      <div class="project-bottom">
        <b-container class="bv-example-row">
          <div class="row">
            <b-col
              v-for="(card, i) in cards"
              :key="i"
              sm="12"
              md="6"
              lg="6"
              xl="4"
              class="project-col"
            >
              <b-card class="project-text" :style="card.colors">
                <h5>{{ card.first }}</h5>
                <p class="second-text">{{ card.second }}</p>
                <p class="third-text">{{ card.third }}</p>
                <p class="forth-text">{{ card.forth }}</p>
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
  name: "ProjectSection",
  data() {
    return {
      cards: [
        { colors: "background-color: rgba(130, 130, 130, 255)" },
        {
          first: "Project Name",
          second: "Client : Rodex Group",
          third:
            "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration.",
          forth: "Rating : ★★★★★",
          colors: "background-color: rgba(230, 109, 109, 235)",
        },
        { colors: "background-color: rgba(130, 130, 130, 255)" },
        { colors: "background-color: rgba(130, 130, 130, 255)" },
        { colors: "background-color: rgba(130, 130, 130, 255)" },
        { colors: "background-color: rgba(130, 130, 130, 255)" },
      ],
    };
  },
};
</script>

<style scoped>
#project .container {
  min-height: 40vh;
  width: 100%;
  display: flex;
}
.project-top h3 {
  display: flex;
  flex-direction: row;
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  text-align: left;
  padding-top: 5rem;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
.project {
  flex-direction: column;
  max-width: 100vw;
  min-height: 90vh;
}
.project-top {
  padding-left: 20vw;
}
/* nav-bar CSS */
.nav-items {
  color: rgba(112, 112, 112, 255);
  font-family: "Roboto Slab", serif;
  font-size: 15px;
}
/* V-Bootstrap's navbar hover color is already !important, so I must use !important in order to change color */
.navbar .navbar-nav .nav-link:hover {
  color: rgba(0, 184, 148, 255) !important;
}
/* End nav-bar CSS */
.project-bottom {
  display: flex;
  flex-wrap: wrap;
  margin-top: 50px;
}
.project-col {
  margin-bottom: 2rem;
}
#project .card-body {
  min-width: 15rem;
  min-height: 20rem;
}
.project-container {
  margin-bottom: 5rem;
}
.project-middle {
  padding-top: 2rem;
  padding-left: 19vw;
}

.project-text h5 {
  padding-top: 2rem;
  font-size: 25px;
  font-weight: lighter;
  text-align: center;
  color: rgba(255, 255, 255, 255);
  font-family: "Roboto Slab", serif;
  margin-bottom: 0;
}
.second-text,
.forth-text {
  text-align: center;
  color: rgba(255, 255, 255, 255);
  font-family: "Roboto Slab", serif;
  font-weight: initial;
  font-size: 12px;
}
.third-text {
  text-align: center;
  color: rgb(223, 223, 223);
  font-family: "PT Sans";
  font-size: 16px;
  margin: 30px 0 40px;
}
</style>
