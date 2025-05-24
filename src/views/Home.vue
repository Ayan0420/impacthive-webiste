<template>
    <section class="container-fluid banner-bg">
        <div class="container">
            <div id="banner" class="row">
                <div class="col-md-6 d-flex flex-column justify-content-center gap-3 py-5">
                    <h1 class="fw-bold text-dark display-4">Empowering Small Businesses with Bold Digital Impact</h1>
                    <p class="fs-5">We help small business owners across the United Kingdom grow through powerful social media management and strategic website design.</p>
                    <div class="btn btn-primary btn-lg rounded-pill px-4 align-self-start">Get in touch for a FREE consultation.</div>
                </div>
            </div>
        </div>
    </section>
    <section class="container my-5">
        <div class="row info-section">
            <div class="col-md-5 d-flex">
                <img class="img-fluid rounded-5 align-self-center" src="@/assets/images/home-image-1.jpg" alt="">
            </div>
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3 mt-4 mt-md-0">
                <h1 class="underline mb-4">What We Do</h1>
                <p class="fs-4">
                    Our team specialises in crafting compelling online presences through bespoke websites and consistent, impactful social media strategies. We combine creativity with data-driven methods to ensure every post, page, and campaign aligns with your goals and drives measurable success.
                </p>
            </div>
        </div>
        <div class="row info-section">
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3 mt-4 mt-md-0 order-2 order-md-1">
                <h1 class="underline mb-4">Who We Help</h1>
                <p class="fs-4">
                    We work with ambitious small business owners, entrepreneurs, and local brands who are ready to strengthen their online visibility, attract the right audience, and build lasting relationships through smart digital marketing.
                </p>
            </div>
            <div class="col-md-5 order-1 order-md-2 d-flex">
                <img class="img-fluid rounded-5 align-self-center" src="@/assets/images/home-image-2.jpg" alt="">
            </div>
        </div>
        <div class="row info-section">
        
            <div class="col-md-5 d-flex">
                <img class="img-fluid rounded-5 align-self-center" src="@/assets/images/home-image-3.jpg" alt="">
            </div>
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3 mt-4 mt-md-0">
                <h1 class="underline mb-4">What Makes Us Unique</h1>
                <p class="fs-4">
                    At <span class="fw-bold text-primary">ImpactHive</span>, we take the time to understand your brand story and translate it into a digital identity that works. We bring clarity to your strategy, consistency to your content, and creativity to every step of the journey.
                </p>
            </div>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h1 class="display-3 text-center text-light fw-bold underline mb-4">Our Services</h1>
            <h3 class="text-center text-light fst-italic">Strategic. Purposeful. Built for Results.</h3>
            <!-- Services Cards -->
            <div class="row mt-5 gap-5">
                <div class="col d-flex justify-content-center">
                    <div class="card" >
                        <img src="@/assets/images/service-1.jpg" class="card-img-top" alt="services 1">
                        <div class="card-body px-5 py-4 d-flex flex-column justify-content-between">
                            <h5 class="card-title display-6">Social Media Management</h5>
                            <p class="card-text">
                                Build a strong online presence with consistent, on-brand, and strategic content.
                            </p>
                            <router-link to="/services" class="btn btn-outline-dark rounded-pill px-4 py-2 align-self-start">I NEED THIS</router-link>
                        </div>  
                    </div>
                </div>
                <div class="col d-flex justify-content-center">
                    <div class="card">
                        <img src="@/assets/images/service-2.jpg" class="card-img-top" alt="services 1">
                        <div class="card-body px-5 py-4 d-flex flex-column justify-content-between">
                            <h5 class="card-title display-6">Website Design & Development</h5>
                            <p class="card-text">
                                For brands and businesses looking for professional, responsive, and conversion-focused websites tailored to your business goals.
                            </p>
                            <router-link to="/services" class="btn btn-outline-dark rounded-pill px-4 py-2 align-self-start">TELL ME HOW</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </section>

    <section id="testimonials" class="container">
        <h1 class="display-4 text-center fw-bold underline mb-4">What Our Clients Are Saying</h1>
        <TestimonialCarousel />
    </section>

    <section id="call-to-action" class="container-fluid d-flex flex-column justify-content-center align-items-center gap-5">

        <h1 class="text-center text-light fw-bold">Let’s create something that connects!</h1>
        <button class="btn btn-outline-light fs-3 rounded-pill px-5 shadow">Start your digital journey with us today.</button>

    
    </section>
</template>

<script setup>
import TestimonialCarousel from '../components/TestimonialCarousel.vue';
</script>

<style scoped>
    #banner {
        min-height: 600px;
    }
    .banner-bg {
        background-image: linear-gradient(to right, rgb(255, 255, 255), 70%, rgba(255, 255, 255, 0)), url(@/assets/images/banner1.jpg);
        background-size: cover;
        background-position: center;
        background-attachment: fixed;
        
        padding-top: 5rem;
        padding-bottom: 5rem;
    }
    .info-section{
        margin-top: 100px;
        margin-bottom: 100px;
    }

    .underline {
        text-decoration: underline;
        text-underline-offset: 10px;
        text-decoration-thickness: 6px;
    }

    #call-to-action{
        min-height: 500px;
        background-image: 
            linear-gradient(to right, rgba(84, 58, 54, 0.70), rgba(84, 58, 54, 0.70)), 
            url(@/assets/images/home-image-4.jpg);
        background-size: cover;
        background-position: center;
        background-attachment: fixed;
    }

    #services {
        padding-top: 5rem;
        padding-bottom: 5rem;
        background-image: 
            linear-gradient(to right, rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.75)), 
            url(@/assets/images/home-image-5.jpg);
        background-size: cover;
        background-position: center;
        background-attachment: fixed;

    }

    #testimonials {
        padding-top: 5rem;
        padding-bottom: 5rem;
    }

    .px-7rem {
        padding-left: 7rem;
        padding-right: 7rem;
    }

    .btn-outline-light {
        backdrop-filter: blur(5px);
        transition: all 0.2s ease-in-out;
    }

    .btn-outline-light:hover {
        background-color: #ae6d71;
        border-color: #ae6d71;
        color: white;
        transform: scale(1.1);
        transition: all 0.2s ease-in-out;
    }


    .card .btn {
        transition: all 0.2s ease-in-out;
    }

    .card .btn:hover {
        transform: scale(1.1);
        transition: all 0.2s ease-in-out;
    }
</style>