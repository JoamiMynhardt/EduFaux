<template>
  <div>
    <Navbar />
    <PageHeader title="Course Details" />
    <CourseDetails />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import CourseDetails from "../components/CourseDetails";
  export default {
    components: {CourseDetails, Footer, Navbar, PageHeader},
    head(){
      return {
        title: "edufaux | Course Details"
      }
    }
  }
</script>
