<template>
  <section class="course-details">
    <div class="container">
        <div class="row">
            <div class="col-lg-8">
                <div class="course-details__content">
                    <p class="course-details__author">
                        by <a href="#">Lauren Taylor</a>
                    </p><!-- /.course-details__author -->

                    <div class="course-details__top">
                        <div class="course-details__top-left">
                            <h2 class="course-details__title">Vue JS Bootcamp</h2>
                            <!-- /.course-details__title -->
                            <div class="course-one__stars">
                                <span class="course-one__stars-wrap">
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                    <i class="fa fa-star"></i>
                                </span><!-- /.course-one__stars-wrap -->
                                <span class="course-one__count">4.8</span><!-- /.course-one__count -->
                                <span class="course-one__stars-count">250</span><!-- /.course-one__stars-count -->
                            </div><!-- /.course-one__stars -->
                        </div><!-- /.course-details__top-left -->
                        <div class="course-details__top-right">
                            <a href="#" class="course-one__category">Development</a><!-- /.course-one__category -->
                        </div><!-- /.course-details__top-right -->
                    </div><!-- /.course-details__top -->
                    <div class="course-one__image">
                        <img src="/assets/images/course-d-1.jpg" alt="">
                        <i class="far fa-heart"></i><!-- /.far fa-heart -->
                    </div><!-- /.course-one__image -->

                    <ul class="course-details__tab-navs list-unstyled nav nav-tabs" role="tablist">
                        <li>
                            <a class="active" role="tab" data-toggle="tab" href="#overview">Overview</a>
                        </li>
                        <li>
                            <a class="" role="tab" data-toggle="tab" href="#curriculum">Curriculum</a>
                        </li>
                        <li>
                            <a class="" role="tab" data-toggle="tab" href="#review">Reviews</a>
                        </li>
                    </ul><!-- /.course-details__tab-navs list-unstyled -->
                    <div class="tab-content course-details__tab-content ">
                        <div class="tab-pane show active  animated fadeInUp" role="tabpanel" id="overview">
                            <p class="course-details__tab-text">
                                Welcome to the Vue JS Bootcamp, your gateway to mastering Vue.js—a powerful JavaScript framework for building modern web applications. In this course, you'll gain hands-on experience, from Vue.js fundamentals to real-world project development, making you a proficient Vue.js developer. Join us on this journey to elevate your web development skills and unlock exciting opportunities in the world of Vue.js.
                            </p><!-- /.course-details__tab-text -->
                            <br>
                            <p class="course-details__tab-text">By the end of this Vue JS Bootcamp, you'll not only have a deep understanding of Vue.js but also have hands-on experience in building modern web applications. Whether you're a beginner looking to start your journey in web development or an experienced developer aiming to expand your skill set, this course offers a transformative learning experience that will propel you to new heights in the world of Vue.js development.</p>
                            <!-- /.course-details__tab-text -->
                        </div><!-- /.course-details__tab-content -->
                        <div class="tab-pane  animated fadeInUp" role="tabpanel" id="curriculum">
                            <h3 class="course-details__tab-title">Starting beginners level course</h3>
                            <!-- /.course-details__title -->
                            <br>
                            <!-- /.course-details__tab-text -->
                            <br>
                            <ul class="course-details__curriculum-list list-unstyled">
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Introduction to Vue.js</a> <span>Preview</span>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">16 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Setting Up Your Development Environment</a> <span>Preview</span>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">7 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Vue Instance and Data Binding</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">15 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Vue Directives: v-bind and v-on</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">23 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Conditional Rendering and Loops</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">12 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Components and Props</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">26 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Event Handling in Vue</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">8 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Vue Router for Single-Page Applications</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">16 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">State Management with Vuex</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">19 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon video-icon">
                                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Real-World Projects with Vue.js</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">15 minutes</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon file-icon">
                                            <i class="fas fa-folder"></i><!-- /.far fa-folder -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">All Resources</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                                <li>
                                    <div class="course-details__curriculum-list-left">
                                        <div class="course-details__meta-icon quiz-icon">
                                            <i class="fas fa-comment"></i><!-- /.fas fa-play -->
                                        </div><!-- /.course-details__icon -->
                                        <a href="#">Quiz</a>
                                    </div><!-- /.course-details__curriculum-list-left -->
                                    <div class="course-details__curriculum-list-right">146 questions</div>
                                    <!-- /.course-details__curriculum-list-right -->
                                </li>
                            </ul><!-- /.course-details__curriculum-list -->
                            <br>
                        </div><!-- /.course-details__tab-content -->
                        <div class="tab-pane  animated fadeInUp" role="tabpanel" id="review">
                            <div class="row">
                                <div class="col-xl-7 d-flex">
                                    <div class="course-details__progress my-auto">
                                        <div class="course-details__progress-item">
                                            <p class="course-details__progress-text">Excellent</p>
                                            <!-- /.course-details__progress-text -->
                                            <div class="course-details__progress-bar">
                                                <span style="width: 95%"></span>
                                            </div><!-- /.course-details__progress-bar -->
                                            <p class="course-details__progress-count">5</p>
                                            <!-- /.course-details__progress-count -->
                                        </div><!-- /.course-details__progress-item -->
                                        <div class="course-details__progress-item">
                                            <p class="course-details__progress-text">Very Good</p>
                                            <!-- /.course-details__progress-text -->
                                            <div class="course-details__progress-bar">
                                                <span style="width: 65%"></span>
                                            </div><!-- /.course-details__progress-bar -->
                                            <p class="course-details__progress-count">2</p>
                                            <!-- /.course-details__progress-count -->
                                        </div><!-- /.course-details__progress-item -->
                                        <div class="course-details__progress-item">
                                            <p class="course-details__progress-text">Average</p>
                                            <!-- /.course-details__progress-text -->
                                            <div class="course-details__progress-bar">
                                                <span style="width: 33%"></span>
                                            </div><!-- /.course-details__progress-bar -->
                                            <p class="course-details__progress-count">1</p>
                                            <!-- /.course-details__progress-count -->
                                        </div><!-- /.course-details__progress-item -->
                                        <div class="course-details__progress-item">
                                            <p class="course-details__progress-text">Poor</p>
                                            <!-- /.course-details__progress-text -->
                                            <div class="course-details__progress-bar">
                                                <span style="width: 0%" class="no-bubble"></span>
                                            </div><!-- /.course-details__progress-bar -->
                                            <p class="course-details__progress-count">0</p>
                                            <!-- /.course-details__progress-count -->
                                        </div><!-- /.course-details__progress-item -->
                                        <div class="course-details__progress-item">
                                            <p class="course-details__progress-text">Terrible</p>
                                            <!-- /.course-details__progress-text -->
                                            <div class="course-details__progress-bar">
                                                <span style="width: 0%" class="no-bubble"></span>
                                            </div><!-- /.course-details__progress-bar -->
                                            <p class="course-details__progress-count">0</p>
                                            <!-- /.course-details__progress-count -->
                                        </div><!-- /.course-details__progress-item -->
                                    </div><!-- /.course-details__progress -->
                                </div><!-- /.col-lg-8 -->
                                <div class="col-xl-5 justify-content-xl-end justify-content-sm-center d-flex">
                                    <div class="course-details__review-box">
                                        <p class="course-details__review-count">4.6</p>
                                        <!-- /.course-details__review-count -->
                                        <div class="course-details__review-stars">
                                            <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                            <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                            <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                            <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                            <i class="fas fa-star-half"></i><!-- /.fas fa-star -->
                                        </div><!-- /.course-details__review-stars -->
                                        <p class="course-details__review-text">30 reviews</p>
                                        <!-- /.course-details__review-text -->
                                    </div><!-- /.course-details__review-box -->
                                </div><!-- /.col-lg-4 -->
                            </div><!-- /.row -->
                            <div class="course-details__comment">
                                <div class="course-details__comment-single">
                                    <div class="course-details__comment-top">
                                        <div class="course-details__comment-right">
                                            <h2 class="course-details__comment-name">Sarah M.</h2>
                                            <!-- /.course-details__comment-name -->
                                            <div class="course-details__comment-meta">
                                                <p class="course-details__comment-date">26 July, 2023</p>
                                                <!-- /.course-details__comment-date -->
                                                <div class="course-details__comment-stars">
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star star-disabled"></i><!-- /.fa fa-star -->
                                                </div><!-- /.course-details__comment-stars -->
                                            </div><!-- /.course-details__comment-meta -->
                                        </div><!-- /.course-details__comment-right -->
                                    </div><!-- /.course-details__comment-top -->
                                    <p class="course-details__comment-text">This Vue.js course is fantastic! The instructor breaks down complex concepts into easy-to-understand lessons. Highly recommended for both beginners and experienced developers.</p>
                                    <!-- /.course-details__comment-text -->
                                </div><!-- /.course-details__comment-single -->
                                <div class="course-details__comment-single">
                                    <div class="course-details__comment-top">
                                        <div class="course-details__comment-right">
                                            <h2 class="course-details__comment-name">John R.</h2>
                                            <!-- /.course-details__comment-name -->
                                            <div class="course-details__comment-meta">
                                                <p class="course-details__comment-date">26 July, 2023</p>
                                                <!-- /.course-details__comment-date -->
                                                <div class="course-details__comment-stars">
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star star-disabled"></i><!-- /.fa fa-star -->
                                                    <i class="fa fa-star star-disabled"></i><!-- /.fa fa-star -->
                                                </div><!-- /.course-details__comment-stars -->
                                            </div><!-- /.course-details__comment-meta -->
                                        </div><!-- /.course-details__comment-right -->
                                    </div><!-- /.course-details__comment-top -->
                                    <p class="course-details__comment-text">Great course for learning Vue.js. The hands-on projects were especially valuable, and the explanations were clear. I wish there were more quizzes though.</p>
                                    <!-- /.course-details__comment-text -->
                                </div><!-- /.course-details__comment-single -->
                            </div><!-- /.course-details__comment -->
                            <form action="#" class="course-details__comment-form">
                                <h2 class="course-details__title">Add a review</h2><!-- /.course-details__title -->
                                <p class="course-details__comment-form-text">Rate this Course? <a href="#" class="fas fa-star"></a><a href="#" class="fas fa-star"></a><a href="#" class="fas fa-star"></a><a href="#" class="fas fa-star"></a><a href="#" class="fas fa-star"></a></p><!-- /.course-details__coment-form-text -->
                                <div class="row">
                                    <div class="col-lg-6">
                                        <input type="text" placeholder="Your Name">
                                        <input type="text" placeholder="Email Address">
                                    </div><!-- /.col-lg-6 -->
                                    <div class="col-lg-12">
                                        <textarea placeholder="Write Message"></textarea>
                                        <button type="submit" class="thm-btn course-details__comment-form-btn">Leave a
                                            Review</button>
                                    </div><!-- /.col-lg-12 -->
                                </div><!-- /.row -->
                            </form><!-- /.course-details__comment-form -->
                        </div><!-- /.course-details__tab-content -->
                    </div><!-- /.tab-content -->
                </div><!-- /.course-details__content -->
            </div><!-- /.col-lg-8 -->
            <div class="col-lg-4">
                <div class="course-details__price">
                    <p class="course-details__price-text">Course price </p><!-- /.course-details__price-text -->
                    <p class="course-details__price-amount">$18.00</p><!-- /.course-details__price-amount -->
                    <a href="#" class="thm-btn course-details__price-btn">Buy This Course</a><!-- /.thm-btn -->
                </div><!-- /.course-details__price -->

                <div class="course-details__meta">
                    <a href="#" class="course-details__meta-link">
                        <span class="course-details__meta-icon">
                            <i class="far fa-clock"></i><!-- /.far fa-clock -->
                        </span><!-- /.course-details__icon -->
                        Durations: <span>10 hours</span>
                    </a><!-- /.course-details__meta-link -->
                    <a href="#" class="course-details__meta-link">
                        <span class="course-details__meta-icon">
                            <i class="far fa-folder-open"></i><!-- /.far fa-folder-open -->
                        </span><!-- /.course-details__icon -->
                        Lectures: <span>6</span>
                    </a><!-- /.course-details__meta-link -->
                    <a href="#" class="course-details__meta-link">
                        <span class="course-details__meta-icon">
                            <i class="fas fa-play"></i><!-- /.fas fa-play -->
                        </span><!-- /.course-details__icon -->
                        Video: <span>8 hours</span>
                    </a><!-- /.course-details__meta-link -->
                    <a href="#" class="course-details__meta-link">
                        <span class="course-details__meta-icon">
                            <i class="far fa-bell"></i><!-- /.far fa-bell -->
                        </span><!-- /.course-details__icon -->
                        Language: <span>English</span>
                    </a><!-- /.course-details__meta-link -->
                </div><!-- /.course-details__meta -->
                <div class="course-details__list">
                    <h2 class="course-details__list-title">Related Courses</h2><!-- /.course-details__list-title -->
                    <div class="course-details__list-item">
                        <div class="course-details__list-content">
                            <a class="course-details__list-author" href="#">by <span>Alicia Martinez</span></a>
                            <h3><a href="#">Vue.js for Beginners: A Step-by-Step Guide</a></h3>
                            <div class="course-details__list-stars">
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <span>3.8</span>
                            </div><!-- /.course-details__list-stars -->
                        </div><!-- /.course-details__list-content -->
                    </div><!-- /.course-details__list-item -->
                    <div class="course-details__list-item">
                        <div class="course-details__list-content">
                            <a class="course-details__list-author" href="#">by <span>Mark Anderson</span></a>
                            <h3><a href="#">Advanced Vue.js Development: Building Interactive Web Apps</a></h3>
                            <div class="course-details__list-stars">
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <span>4.8</span>
                            </div><!-- /.course-details__list-stars -->
                        </div><!-- /.course-details__list-content -->
                    </div><!-- /.course-details__list-item -->
                    <div class="course-details__list-item">
                        <div class="course-details__list-content">
                            <a class="course-details__list-author" href="#">by <span>Emily Davis</span></a>
                            <h3><a href="#">Vue.js and Vuex: State Management Mastery</a></h3>
                            <div class="course-details__list-stars">
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <i class="fas fa-star"></i><!-- /.fas fa-star -->
                                <span>4.5</span>
                            </div><!-- /.course-details__list-stars -->
                        </div><!-- /.course-details__list-content -->
                    </div><!-- /.course-details__list-item -->
                </div><!-- /.course-details__list -->
            </div><!-- /.col-lg-4 -->
        </div><!-- /.row -->
    </div><!-- /.container -->
</section>
</template>

<script>
    export default {
        name: "CourseDetails"
    }
</script>

<style scoped>

</style>
