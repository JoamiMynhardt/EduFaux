<template>
  <div>
    <Navbar />
    <PageHeader title="Courses" />
    <Course />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import Course from "../components/Course";
  export default {
    components: {Course, Footer, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | Course"
      }
    }
  }
</script>
