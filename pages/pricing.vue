<template>
  <div>
    <Navbar />
    <PageHeader title="Membership Options" />
    <PricingPage />
    <CallToAction />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import PricingPage from "../components/PricingPage";
  import CallToAction from "../components/CallToAction";
  import Footer from "../components/Footer";
  export default {
    components: {Footer, CallToAction, PricingPage, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | Pricing"
      }
    }
  }
</script>

<style scoped>
  .block-title .block-title__title {
    display: none;
  }
</style>
