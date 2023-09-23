<template>
    <div class="banner-wrapper">
        <section class="banner banner-carousel__one no-dots owl-theme owl-carousel">
            <div class="banner__slide banner__slide-one"
                :style="{ backgroundImage: `url(/assets/images/slider-2-1.jpg)` }">
                <div class="container">
                    <div class="row no-gutters">
                        <div class="col-xl-12">
                            <h3 class="banner__title banner__light-color">Explore Endless Possibilities</h3><!-- /.banner__title -->
                            <a href="#" class="thm-btn banner__btn">Learn More</a>
                        </div><!-- /.col-xl-12 -->
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.banner__slide -->
            <div class="banner__slide banner__slide-two"
                :style="{ backgroundImage: `url(/assets/images/slider-2-2.jpg)` }">
                <div class="container">
                    <div class="row no-gutters">
                        <div class="col-xl-12">
                            <h3 class="banner__title banner__light-color">Unlock Your Potential Today</h3><!-- /.banner__title -->
                            <a href="#" class="thm-btn banner__btn">Learn More</a>
                        </div><!-- /.col-xl-12 -->
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.banner__slide -->
        </section><!-- /.banner -->
        <div class="banner-carousel-btn">
            <a href="#" class="banner-carousel-btn__left-btn"><i class="edufaux-icon-left-arrow"></i></a>
            <a href="#" class="banner-carousel-btn__right-btn"><i class="edufaux-icon-right-arrow"></i></a>
        </div><!-- /.banner-carousel-btn -->
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped></style>
