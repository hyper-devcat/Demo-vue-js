<template>
  <div id="app">
    <HeroSection>
      <HeroPage msg="Professional Graphic Designer" />
    </HeroSection>
    <AboutSection />
    <ServiceSection />
    <SkillSection />
    <ProjectSection />
    <ClientSection />
    <FormSection />
    <NewsSection />
    <FooterSection>
      <FooterLogo />
      <FooterMain />
    </FooterSection>
  </div>
</template>

<script>
import HeroPage from "./components/HeroPage.vue";
import HeroSection from "./components/HeroSection.vue";
import AboutSection from "./components/AboutSection.vue";
import ServiceSection from "./components/ServiceSection.vue";
import SkillSection from "./components/SkillSection.vue";
import ProjectSection from "./components/ProjectSection.vue";
import ClientSection from "./components/ClientSection.vue";
import FormSection from "./components/FormSection.vue";
import NewsSection from "./components/NewsSection.vue";
import FooterSection from "./components/FooterSection.vue";
import FooterLogo from "./components/FooterLogo.vue";
import FooterMain from "./components/FooterMain.vue";

export default {
  name: "App",
  components: {
    HeroPage,
    HeroSection,
    AboutSection,
    ServiceSection,
    SkillSection,
    ProjectSection,
    ClientSection,
    FormSection,
    NewsSection,
    FooterSection,
    FooterLogo,
    FooterMain,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}
/* #app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
} */
</style>
