<template>
  <div id="container">
    <HeaderImage/>
    <ServiceComponent/>
    <Footer/>
  </div>
  <router-view/>
</template>

<script>
// @ is an alias to /src
import HeaderImage from "@/components/HeaderImage.vue";
import Footer from "@/components/Footer.vue";
import ServiceComponent from "@/components/ServiceComponent.vue";

export default {
  name: "Home",
  components: {
    HeaderImage, Footer, ServiceComponent
  }
};
</script>