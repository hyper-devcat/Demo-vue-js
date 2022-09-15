<template>
  <!-- Grey Button "Download CV" -->
  <b-button class="btn-grey" variant="outline-light">
    {{ label }}
  </b-button>
</template>

<script>
export default {
  name: "CvButton",
  props: {
    label: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
.btn-grey {
  display: inline-block;
  padding: 10px 25px;
  margin: auto;
  color: rgba(254, 254, 254, 255);
  background-color: rgba(50, 50, 50, 255);
  font-size: 1rem;
  font-weight: lighter;
  margin-top: 2rem;
  transition: 0.3s ease;
  text-decoration: none;
  font-family: "Roboto Slab", serif;
}

.btn-grey:hover {
  color: white;
  background-color: grey;
}
</style>
