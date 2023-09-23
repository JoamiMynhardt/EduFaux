<template>
  <div>
    <Navbar />
    <PageHeader title="Become a Teacher" />
    <BecomeTeacher />
    <Footer />
  </div>
</template>
<script>

  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import BecomeTeacher from "../components/BecomeTeacher";
  export default {
    components: {BecomeTeacher, Footer, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | Become Teacher"
      }
    }
  }
</script>
