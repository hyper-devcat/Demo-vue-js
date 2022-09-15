<template>
  <!-- Section "Hi Myself Jhon Smith" -->
  <section id="hero">
    <NavItem />
    <div class="hero container">
      <!-- In order to fill in the main title-->
      <slot />
    </div>
  </section>
</template>

<script>
import NavItem from "./NavItem.vue";
export default {
  name: "HeroSection",
  components: { NavItem },
};
</script>

<style scoped>
#hero .container {
  min-height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
}
#hero {
  background-image: url("img/Image-shape.png");
  background-size: cover;
  background-position: top center;
  position: relative;
  z-index: 1;
}
#hero::after {
  /* content: ""; */
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  background-color: white;
  opacity: 0.1;
}

#hero .hero {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 50px;
  justify-content: flex-start;
}
</style>
