<template>
  <div id="app" :class="mode">
    <Nav />
    <Banner />
    <Capability />
    <Project />
    <Contact />
    <Partners />
    <Testimonial />
    <Vairable /> 
    <Footer />
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Banner from "./components/Banner.vue";
import Capability from "./components/Capability.vue";
import Project from "./components/Project.vue";
import Contact from "./components/Contact.vue";
import Partners from "./components/Partners.vue";
import Testimonial from "./components/Testimonial.vue";
import Vairable from "./components/Vairable.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  data() {
    return {
      mode: "dark",
    };
  },
  components: {
    Nav,
    Banner,
    Capability,
    Project,
    Contact,
    Partners,
    Testimonial,
    Vairable,
    Footer,
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
#app {
  font-family: "Poppins", sans-serif;
  background-color: #181818;
  color: #ffffff;
  font-size: 16px;
}
</style>
