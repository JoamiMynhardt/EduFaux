<template>
    <div>
        <footer class="site-footer">
            <div class="site-footer__upper">
                <div class="container">
                    <div class="row">
                        <div class="col-xl-3 col-lg-6 col-sm-12">
                            <div class="footer-widget footer-widget__contact">
                                <h2 class="footer-widget__title">Courses</h2><!-- /.footer-widget__title -->
                                <ul class="list-unstyled footer-widget__course-list">
                                    <li>
                                        <h2><a href="course-details.html">Digital Marketing Essentials</a></h2>
                                        <p>Samantha Carter</p>
                                    </li>
                                    <li>
                                        <h2><a href="course-details.html">Cyber security Fundamentals</a></h2>
                                        <p>David Foster</p>
                                    </li>
                                </ul><!-- /.footer-widget__course-list -->
                            </div><!-- /.footer-widget -->
                        </div><!-- /.col-lg-3 -->
                        <div class="col-xl-3 col-lg-6 col-sm-12">
                            <div class="footer-widget footer-widget__contact padding-185">
                                <ul class="list-unstyled footer-widget__course-list">
                                    <li>
                                        <h2><a href="course-details.html">AI Essentials</a></h2>
                                        <p>Ethan Watson</p>
                                    </li>
                                    <li>
                                        <h2><a href="course-details.html">Vue JS Bootcamp</a></h2>
                                        <p>Lauren Taylor</p>
                                    </li>
                                </ul><!-- /.footer-widget__course-list -->
                            </div><!-- /.footer-widget -->
                        </div><!-- /.col-lg-3 -->
                        <div class="col-xl-3 col-lg-6 col-sm-12">
                            <div class="footer-widget footer-widget__link">
                                <h2 class="footer-widget__title">Explore</h2><!-- /.footer-widget__title -->
                                <div class="footer-widget__link-wrap">
                                    <ul class="list-unstyled footer-widget__link-list">
                                        <li><a href="/courses">Courses</a></li>
                                        <li><a href="/pricing">Pricing</a></li>
                                        <li><a href="/become-teacher">Become A Teacher</a></li>
                                        <li><a href="faq">FAQs</a></li>
                                        <li><a href="/contact">Contact</a></li>
                                    </ul><!-- /.footer-widget__link-list -->
                                </div><!-- /.footer-widget__link-wrap -->
                            </div><!-- /.footer-widget -->
                        </div><!-- /.col-lg-3 -->
                        <div class="col-xl-3 col-lg-6 col-sm-12">
                            <div class="footer-widget footer-widget__about">
                                <h2 class="footer-widget__title">About</h2><!-- /.footer-widget__title -->
                                <p class="footer-widget__text">We're your gateway to a world of learning and teaching, fostering a global community of knowledge seekers.</p><!-- /.footer-widget__text -->
                                <div class="footer-widget__btn-block">
                                    <a href="/contact" class="thm-btn">Contact</a><!-- /.thm-btn -->
                                    <a href="/courses" class="thm-btn">Courses</a><!-- /.thm-btn -->
                                </div><!-- /.footer-widget__btn-block -->
                            </div><!-- /.footer-widget -->
                        </div><!-- /.col-lg-3 -->
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.site-footer__upper -->
            <div class="site-footer__bottom">
                <div class="container">
                    <p class="site-footer__copy">
                        &copy; Copyright by <a href="https://motioncodelabs.co.za" target="_blank">motioncodelabs.co.za</a>
                    </p>
                    <div class="site-footer__social">
                        <a href="#" data-target="html" class="scroll-to-target site-footer__scroll-top"><i
                                class="edufaux-icon-top-arrow"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-facebook-square"></i></a>
                        <a href="#"><i class="fab fa-pinterest-p"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div><!-- /.site-footer__social -->
                    <!-- /.site-footer__copy -->
                </div><!-- /.container -->
            </div><!-- /.site-footer__bottom -->
        </footer>
        <div class="search-popup">
            <div class="search-popup__overlay custom-cursor__overlay">
                <div class="cursor"></div>
                <div class="cursor-follower"></div>
            </div><!-- /.search-popup__overlay -->
            <div class="search-popup__inner">
                <form action="#" class="search-popup__form">
                    <input type="text" name="search" placeholder="Type here to Search....">
                    <button type="submit"><i class="edufaux-icon-magnifying-glass"></i></button>
                </form>
            </div><!-- /.search-popup__inner -->
        </div>
    </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped></style>
