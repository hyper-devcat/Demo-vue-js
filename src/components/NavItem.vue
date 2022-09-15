<template>
  <!-- Nav Bar of section "Hi Myself Jhon Smith" (HeroSection)-->
  <div class="nav-bar">
    <!-- Because there is no background-color of navbar, I  didn't use fixed-top. -->
    <b-navbar toggleable="lg">
      <b-navbar-brand href="#hero">
        <img
          class="logo"
          alt="Vue logo"
          src="../assets/logo.png"
          align="left"
        />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav>
            <b-nav-item class="nav-items" href="#hero">Home</b-nav-item>
            <b-nav-item class="nav-items" href="#about">About</b-nav-item>
            <b-nav-item class="nav-items" href="#services">Services</b-nav-item>
            <b-nav-item class="nav-items" href="#project">Protfolio</b-nav-item>
            <b-nav-item class="nav-items" href="#news">Blog</b-nav-item>
            <b-button class="contactme" variant="outline-light"
              >Contact Me
            </b-button>
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NavItem",
};
</script>

<style scoped>
.logo {
  padding-left: 2rem;
}
.nav-bar {
  padding-top: 2rem;
  margin: 0 1rem;
}
.nav-items {
  font-family: "Roboto Slab", serif;
  font-size: 14px;
  font-weight: bold;
  padding-right: 1rem;
}

.contactme {
  background-color: rgba(0, 184, 148, 255);
  font-family: "Roboto Slab", serif;
  font-size: 14px;
}
</style>
