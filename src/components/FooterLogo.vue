<template>
  <!-- 5 Logo above Footer -->
  <div id="logo">
    <b-container class="bv-example-row">
      <div class="logo container d-flex justify-content-between row">
        <img src="../assets/Vector.png" alt="img" />
        <img src="../assets/Vector(1).png" alt="img" />
        <img src="../assets/Vector(2).png" alt="img" />
        <img src="../assets/Vector(3).png" alt="img" />
        <img src="../assets/Vector(4).png" alt="img" />
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "FooterLogo",
};
</script>

<style scoped>
img {
  margin-top: 2rem;
  margin-bottom: 5rem;
  text-align: center;
}
#logo.row {
  margin-left: 0;
  margin-right: 0;
}
</style>
