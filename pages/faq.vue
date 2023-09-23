<template>
  <div>
    <Navbar />
    <PageHeader title="FAQ" />
    <Faq />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import Faq from "../components/Faq";
  export default {
    components: {Faq, Footer, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | FAQ"
      }
    }
  }
</script>
