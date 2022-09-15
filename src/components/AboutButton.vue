<template>
  <!-- Green Button "About me"  to AboutSection.vue-->
  <b-button href="#about" class="btn-green" variant="outline-light">
    {{ label }}
  </b-button>
</template>

<script>
export default {
  name: "AboutButton",
  props: {
    label: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.btn-green {
  display: inline-block;
  padding: 10px 40px;
  margin: auto;
  color: rgba(254, 254, 254, 255);
  background-color: rgba(0, 184, 148, 255);
  font-size: 1rem;
  font-weight: lighter;
  margin-top: 2rem;
  transition: 0.3s ease;
  text-decoration: none;
  font-family: "Roboto Slab", serif;
}

.btn-green:hover {
  color: white;
  background-color: mediumaquamarine;
}
</style>
