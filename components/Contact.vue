<template>
    <div>
        <section class="contact-info-one">
            <div class="container">
                <div class="row">
                    <div class="col-lg-4">
                        <div class="contact-info-one__single wow fadeInDown animated" data-wow-duration="1500ms"
                            style="visibility: visible; animation-duration: 1500ms; animation-name: fadeInDown;">
                            <div class="contact-info-one__icon"><i
                                    class="edufaux-icon-manager"></i><!-- /.edufaux-icon-manager -->
                            </div><!-- /.contact-info-one__icon -->
                            <h2 class="contact-info-one__title">About Us </h2><!-- /.contact-info-one__title -->
                            <p class="contact-info-one__text">We're your gateway to a world of learning and teaching, fostering a global community of knowledge seekers.</p><!-- /.contact-info-one__text -->
                        </div><!-- /.contact-info-one__single -->
                    </div><!-- /.col-lg-4 -->
                    <div class="col-lg-4">
                        <div class="contact-info-one__single wow fadeInUp animated" data-wow-duration="1500ms"
                            style="visibility: visible; animation-duration: 1500ms; animation-name: fadeInUp;">
                            <div class="contact-info-one__icon"><i class="edufaux-icon-placeholder"></i>
                                <!-- /.edufaux-icon-manager -->
                            </div><!-- /.contact-info-one__icon -->
                            <h2 class="contact-info-one__title">Our Address</h2><!-- /.contact-info-one__title -->
                            <p class="contact-info-one__text">
                                1234 Elm Street <br />
                                Suite 567 <br />
                                Educationville, USA <br />
                                12345</p><!-- /.contact-info-one__text -->
                        </div><!-- /.contact-info-one__single -->
                    </div><!-- /.col-lg-4 -->
                    <div class="col-lg-4">
                        <div class="contact-info-one__single wow fadeInDown animated" data-wow-duration="1500ms"
                            style="visibility: visible; animation-duration: 1500ms; animation-name: fadeInDown;">
                            <div class="contact-info-one__icon"><i
                                    class="edufaux-icon-contact"></i><!-- /.edufaux-icon-manager -->
                            </div><!-- /.contact-info-one__icon -->
                            <h2 class="contact-info-one__title">Contact Info</h2><!-- /.contact-info-one__title -->
                            <p class="contact-info-one__text">support@edufaux.com <br>
                                Phone: +1 (555) 123-4567 <br> &nbsp; </p><!-- /.contact-info-one__text -->
                        </div><!-- /.contact-info-one__single -->
                    </div><!-- /.col-lg-4 -->
                </div><!-- /.row -->
            </div><!-- /.container -->
        </section>
        <section class="contact-one">
            <div class="container">
                <h2 class="contact-one__title text-center">Get in touch <br>
                    with us</h2><!-- /.contact-one__title -->
                <form action="/assets/inc/sendemail.php" class="contact-one__form contact-form-validated"
                    novalidate="novalidate">
                    <div class="row low-gutters">
                        <div class="col-lg-6">
                            <input type="text" name="name" placeholder="Your Name">
                        </div><!-- /.col-lg-6 -->
                        <div class="col-lg-6">
                            <input type="text" placeholder="Email Address" name="email">
                        </div><!-- /.col-lg-6 -->
                        <div class="col-lg-12">
                            <textarea placeholder="Write Message" name="message"></textarea>
                            <div class="text-center">
                                <button type="submit" class="contact-one__btn thm-btn">Submit Comment</button>
                            </div><!-- /.text-center -->
                        </div><!-- /.col-lg-12 -->
                    </div><!-- /.row -->
                </form><!-- /.contact-one__form -->
                <div class="result text-center"></div><!-- /.result -->
            </div><!-- /.container -->
        </section>
    </div>
</template>

<script>
export default {
    name: "Contact"
}
</script>

<style scoped></style>
