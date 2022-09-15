<template>
  <!-- Middle of section "Hi Myself Jhon Smith" (HeroSection)-->
  <div id="heropage">
    <h2>
      <span class="hi">Hi Myself</span>
      <span class="jhon"> Jhon Smith</span>
    </h2>
    <h1>{{ msg }}</h1>
    <p>
      There are many variations of passages of Lorem Ipsum available, but the
      majority have suffered alteration in some form, by injected humor,
    </p>
    <AboutButton class="abutton" label="About Me" />
    <CvButton label="Download CV" />
  </div>
</template>

<script>
import AboutButton from "./AboutButton.vue";
import CvButton from "./CvButton.vue";
export default {
  name: "HeroPage",
  props: {
    msg: String,
  },
  components: { AboutButton, CvButton },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 48px;
  text-align: left;
}

p {
  text-align: left;
  margin-top: 2rem;
  font-size: 16px;
  font-family: "PT Sans";
  color: rgba(112, 112, 112, 255);
}

h2 .hi {
  color: rgba(50, 50, 50, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 28px;
}

h2 .jhon {
  color: rgba(0, 184, 148, 255);
  font-family: "Roboto Slab", serif;
  font-weight: bold;
  font-size: 28px;
}

.abutton {
  margin-right: 2rem;
}
</style>
