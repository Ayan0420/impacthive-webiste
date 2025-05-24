<template>
    <section class="container-fluid banner-bg">
        <div class="container">
            <div id="banner" class="row">
                <div class="col-md-6 d-flex flex-column justify-content-center">
                    <h1 class="fw-bold text-primary">Empowering Small Businesses with Bold Digital Impact</h1>
                    <p class="fs-5">At ImpactHive Marketing, we help small business owners across the United Kingdom grow through powerful social media management and strategic website design. Whether you're launching your brand or scaling your presence, we’re here to turn your vision into results. We don’t just deliver digital services—we build digital confidence.</p>
                    <div class="btn btn-primary btn-lg rounded-pill px-4 mt-5">Get in touch for a FREE consultation.</div>
                </div>
            </div>
        </div>
    </section>
    <section class="container my-5">
        <div class="row info-section">
            <div class="col-md-5">
                <img class="img-fluid rounded-5" src="@/assets/images/home-image-1.jpg" alt="">
            </div>
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3">
                <h1>What We Do</h1>
                <p class="">
                    At ImpactHive Marketing, we specialise in social media management and website design that helps small businesses stand out and grow in today’s digital world. We don’t just create content or build websites — we create strategic, high-performing brand experiences that convert attention into trust and trust into action. From eye-catching Instagram reels to custom-built websites, every element we craft is designed to deliver real impact.
                </p>
                <p>
                    Our work goes beyond aesthetics. We bring strategy, structure, and purpose to every post and page. Whether it’s a content calendar that builds consistency or a website that reflects your brand’s personality and goals, we partner with you to ensure everything aligns with your long-term vision. Our goal is simple — help you make a lasting impression and turn your online presence into a powerful business tool.
                </p>
            </div>
        </div>
        <div class="row info-section">
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3">
                <h1>Who We Help</h1>
                <p class="">
                    We work with small business owners across the United Kingdom who are ready to take their online presence seriously. Whether you're a start-up just getting off the ground or a growing brand looking for more structure and support, we tailor our services to meet your stage and ambitions. If you’re juggling too much, stuck with outdated visuals, or unsure how to connect with your audience online, we're here to guide and support you.
                </p>
                <p>
                    Our clients come from a range of industries — from beauty and wellness to professional services, retail, and local trades. What they all have in common is a desire to grow confidently and consistently online. We step in as your creative partner, making digital marketing feel less overwhelming and more empowering, so you can focus on running your business while we focus on making it visible.
                </p>
            </div>
            <div class="col-md-5">
                <img class="img-fluid rounded-5" src="@/assets/images/home-image-2.jpg" alt="">
            </div>
        </div>
        <div class="row info-section">
        
            <div class="col-md-5">
                <img class="img-fluid rounded-5" src="@/assets/images/home-image-3.jpg" alt="">
            </div>
            <div class="col-md-7 d-flex flex-column justify-content-center align-items-center gap-3">
                <h1>What Makes Us Unique</h1>
                <p class="">
                    At ImpactHive, we combine strategy with creativity, professionalism with approachability, and expertise with heart. Led by Charlotte and supported by a trusted team, we bring over four years of hands-on experience in social media and web design. But it’s not just about what we do — it’s how we do it. We take time to understand your goals, communicate clearly, and deliver with consistency and care.
                </p>
                <p>
                    Unlike agencies that offer cookie-cutter solutions, we customise every plan to fit your brand, your voice, and your growth journey. From bespoke content strategies to websites built around your goals and budget, we focus on what truly moves the needle. Our clients don’t just get deliverables — they get clarity, confidence, and a digital presence that finally feels like them.
                </p>
            </div>
        </div>
    </section>
    <section id="call-to-action" class="container-fluid d-flex flex-column justify-content-center align-items-center gap-3">

        <h1>Let’s create something that connects!</h1>
        <button class="btn btn-light fs-3 rounded-pill px-5">Start your digital journey with us today.</button>

    
    </section>
</template>

<style scoped>
    #banner {
        min-height: 600px;
    }
    .banner-bg {
        background-image: linear-gradient(to right, rgb(255, 255, 255), 70%, rgba(255, 255, 255, 0)), url(@/assets/images/banner1.jpg);
        background-size: cover;
        background-position: center;
    }
    .info-section{
        margin-top: 100px;
        margin-bottom: 100px;
    }
    #call-to-action{
        min-height: 300px;
        background-color: #c29c97;
    }
</style>