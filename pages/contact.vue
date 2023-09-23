<template>
  <div>
    <Navbar />
    <PageHeader title="Contact" />
    <Contact />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import Contact from "../components/Contact";
  export default {
    components: {Contact, Footer, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | Contact"
      }
    }
  }
</script>
