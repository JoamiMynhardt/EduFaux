<template>
    <header class="site-header site-header__header-two ">
        <nav class="navbar navbar-expand-lg navbar-light header-navigation stricky">
            <div class="container clearfix">
                <!-- Brand and toggle get grouped for better mobile display -->
                <div class="logo-box clearfix">
                    <a class="navbar-brand" href="/">
                        <img src="/assets/images/logo.png" class="main-logo" width="128" alt="Awesome Image" />
                    </a>
                    <button class="menu-toggler" data-target=".main-navigation">
                        <span class="edufaux-icon-menu"></span>
                    </button>
                    <form action="#" class="header__search-form">
                        <input type="text" placeholder="Search courses">
                        <button type="submit"><i class="edufaux-icon-magnifying-glass"></i>
                            <!-- /.edufaux-icon-magnifying-glass --></button>
                    </form>
                </div><!-- /.logo-box -->
                <!-- Collect the nav links, forms, and other content for toggling -->
                <div class="main-navigation">
                    <ul class=" navigation-box">
                        <li>
                            <nuxt-link to="/">Home</nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/courses">Courses</nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/pricing">Pricing</nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/become-teacher">Become A Teacher</nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/faq">FAQs</nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/contact">Contact</nuxt-link>
                        </li>
                    </ul>
                </div><!-- /.navbar-collapse -->
                <div class="right-side-box">
                    <div class="header__social">
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-facebook-square"></i></a>
                        <a href="#"><i class="fab fa-pinterest-p"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div><!-- /.header__social -->
                </div><!-- /.right-side-box -->
            </div>
            <!-- /.container -->
        </nav>
        <div class="site-header__decor">
            <div class="site-header__decor-row">
                <div class="site-header__decor-single">
                    <div class="site-header__decor-inner-1"></div><!-- /.site-header__decor-inner -->
                </div><!-- /.site-header__decor-single -->
                <div class="site-header__decor-single">
                    <div class="site-header__decor-inner-2"></div><!-- /.site-header__decor-inner -->
                </div><!-- /.site-header__decor-single -->
                <div class="site-header__decor-single">
                    <div class="site-header__decor-inner-3"></div><!-- /.site-header__decor-inner -->
                </div><!-- /.site-header__decor-single -->
            </div><!-- /.site-header__decor-row -->
        </div><!-- /.site-header__decor -->
    </header>
</template>

<script>
export default {
    name: "Navbar"
}
</script>

<style scoped></style>
