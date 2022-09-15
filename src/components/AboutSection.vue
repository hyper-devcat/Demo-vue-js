<template>
  <!-- Section "About Me" : Presentation of author-->
  <section id="about">
    <div class="about container">
      <div class="col-left">
        <!-- Title -->
        <h5>About Me</h5>
        <p><span class="under-about">&emsp;&emsp;&emsp;</span></p>
        <h3>
          Creative Graphic Designer <br />
          Creat Awesome Project As You Need
        </h3>
        <!-- Presentation -->
        <p>
          <span class="paragraph">
            There are many variations of passages of Lorem Ipsum available, but
            the majority have suffered alteration in some form, by injected
            humor, or randomised words which don't look even sightly
            believable.If you are going to use a passage of Lorem Ipsum, you
            need to be sure there isn't anything.
          </span>
        </p>
      </div>
      <div class="col-right">
        <div class="about-img">
          <img src="/assets/about.jpg" class="responsive" alt="img" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutSection",
};
</script>

<style scoped>
#about .container {
  min-height: 40vh;
  min-width: 100px;
  display: flex;
  align-items: center;
}
.under-about {
  padding: 0;
  color: rgba(0, 184, 148, 255);
  font-weight: 800;
  border-top: solid;
  border-width: 2px;
}
h5 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
}
h3 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  margin-bottom: 3rem;
  position: relative;
  text-decoration-line: underline;
  text-decoration-style: solid;
  text-decoration-color: rgba(196, 234, 230, 255);
  text-decoration-thickness: 5px;
  text-decoration-skip-ink: none;
}
.paragraph {
  font-family: "PT Sans";
  color: rgba(112, 112, 112, 255);
}
#about .about {
  text-align: left;
  max-width: 1200px;
  padding: 100px 30px;
  margin: 0 auto;
}
/* "About Me" reponsive */
@media (max-width: 900px) {
  #about .container {
    flex-direction: column;
  }
}
@media (min-width: 1300px) {
  .responsive {
    max-width: 20vw;
    height: auto;
  }
}
/* 3 circles reponsive */
.responsive {
  max-width: 70vw;
  height: auto;
}
</style>
