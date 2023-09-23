<template>
  <div>
    <Navbar />
    <Banner />
    <CourseCategory />
    <CourseHome />
    <CallToActionTwo />
    <Footer />
  </div>
</template>
<script>
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";
  import Banner from "../components/Banner";
  import CourseCategory from "../components/CourseCategory";
  import CourseHome from "../components/CourseHome";
  import CallToActionTwo from "../components/CallToActionTwo";
  export default {
    components: {
      CallToActionTwo,
      CourseHome,
      CourseCategory,
      Banner,
      Footer,
      Navbar
    },
    head(){
      return{
        title: "EduFaux | Home"
      }
    }
  }
</script>
