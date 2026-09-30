# About page

Below is a complete, responsive about.html page matching your existing XYZ Web Solutions Bootstrap website, with About, mission, services, process, technologies, values, and CTA sections.
```html
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Learn about XYZ Web Solutions, a web development company providing website development, WordPress, e-commerce, web application and API development services.">

    <meta name="keywords"
          content="web development company, website development, WordPress development, e-commerce development, web application development, API development">

    <meta name="author"
          content="XYZ Web Solutions">

    <meta name="robots"
          content="index, follow">

    <meta name="theme-color"
          content="#212529">

    <title>About Us | XYZ Web Solutions</title>


    <!-- ==================================================
         Bootstrap 5
    =================================================== -->

    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
        rel="stylesheet">


    <!-- ==================================================
         Bootstrap Icons
    =================================================== -->

    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">


    <!-- ==================================================
         Custom CSS
    =================================================== -->

    <style>

        body {
            background-color: #f8f9fa;
            color: #212529;
        }


        /* ================================================
           NAVBAR
        ================================================= */

        .navbar-brand {
            font-weight: 700;
            letter-spacing: 0.3px;
        }


        /* ================================================
           PAGE HEADER
        ================================================= */

        .page-header {

            background:
                linear-gradient(
                    135deg,
                    #212529,
                    #343a40
                );

            color: #fff;

            padding: 100px 0;

        }


        .page-header h1 {

            font-size: 3rem;
            font-weight: 700;

        }


        .page-header p {

            max-width: 750px;
            margin: 0 auto;

        }


        /* ================================================
           SECTION
        ================================================= */

        .section-padding {

            padding: 80px 0;

        }


        .section-title {

            font-weight: 700;

        }


        .section-subtitle {

            max-width: 700px;
            margin: 0 auto;
            color: #6c757d;

        }


        /* ================================================
           ABOUT IMAGE
        ================================================= */

        .about-image {

            min-height: 420px;

            background:
                linear-gradient(
                    135deg,
                    #212529,
                    #0d6efd
                );

            border-radius: 20px;

            display: flex;
            align-items: center;
            justify-content: center;

            color: #fff;

            overflow: hidden;

        }


        .about-image i {

            font-size: 9rem;
            opacity: 0.9;

        }


        /* ================================================
           FEATURE BOX
        ================================================= */

        .feature-box {

            padding: 25px;

            background: #fff;

            border-radius: 15px;

            height: 100%;

            border: 1px solid #e9ecef;

            transition: 0.3s;

        }


        .feature-box:hover {

            transform: translateY(-5px);

            box-shadow:
                0 10px 30px
                rgba(0, 0, 0, 0.08);

        }


        .feature-icon {

            width: 55px;
            height: 55px;

            display: flex;
            align-items: center;
            justify-content: center;

            border-radius: 12px;

            background: #e7f1ff;

            color: #0d6efd;

            font-size: 1.5rem;

            margin-bottom: 20px;

        }


        /* ================================================
           VALUES
        ================================================= */

        .value-card {

            background: #fff;

            padding: 30px;

            border-radius: 15px;

            height: 100%;

            border: 1px solid #e9ecef;

        }


        .value-card i {

            font-size: 2.2rem;

            color: #0d6efd;

            margin-bottom: 20px;

        }


        /* ================================================
           TECHNOLOGIES
        ================================================= */

        .technology {

            background: #fff;

            border: 1px solid #dee2e6;

            border-radius: 10px;

            padding: 18px 15px;

            text-align: center;

            font-weight: 600;

            transition: 0.3s;

        }


        .technology:hover {

            transform: translateY(-3px);

            border-color: #0d6efd;

            box-shadow:
                0 5px 20px
                rgba(0, 0, 0, 0.06);

        }


        .technology i {

            display: block;

            font-size: 1.8rem;

            margin-bottom: 8px;

            color: #0d6efd;

        }


        /* ================================================
           PROCESS
        ================================================= */

        .process-number {

            width: 60px;
            height: 60px;

            display: flex;
            align-items: center;
            justify-content: center;

            border-radius: 50%;

            background: #0d6efd;

            color: #fff;

            font-size: 1.2rem;

            font-weight: 700;

            margin: 0 auto 20px;

        }


        .process-card {

            text-align: center;

            padding: 25px;

        }


        /* ================================================
           CTA
        ================================================= */

        .cta-section {

            background:
                linear-gradient(
                    135deg,
                    #212529,
                    #343a40
                );

            color: #fff;

        }


        /* ================================================
           FOOTER
        ================================================= */

        footer {

            background: #212529;

            color: #adb5bd;

        }


        footer a {

            color: #adb5bd;

            text-decoration: none;

        }


        footer a:hover {

            color: #fff;

        }


        /* ================================================
           RESPONSIVE
        ================================================= */

        @media (max-width: 768px) {

            .page-header {

                padding: 70px 0;

            }

            .page-header h1 {

                font-size: 2.3rem;

            }

            .section-padding {

                padding: 60px 0;

            }

            .about-image {

                min-height: 300px;

            }

            .about-image i {

                font-size: 6rem;

            }

        }

    </style>

</head>


<body>


<!-- =====================================================
     NAVBAR
====================================================== -->

<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">

    <div class="container">

        <a class="navbar-brand"
           href="index.html">

            <i class="bi bi-code-slash me-2"></i>

            XYZ Web Solutions

        </a>


        <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#mainNavbar"
            aria-controls="mainNavbar"
            aria-expanded="false"
            aria-label="Toggle navigation">

            <span class="navbar-toggler-icon"></span>

        </button>


        <div class="collapse navbar-collapse"
             id="mainNavbar">

            <ul class="navbar-nav ms-auto">


                <li class="nav-item">

                    <a class="nav-link"
                       href="index.html">

                        Home

                    </a>

                </li>


                <li class="nav-item">

                    <a class="nav-link"
                       href="index.html#services">

                        Services

                    </a>

                </li>


                <li class="nav-item">

                    <a class="nav-link active"
                       aria-current="page"
                       href="about.html">

                        About

                    </a>

                </li>


                <li class="nav-item">

                    <a class="nav-link"
                       href="index.html#portfolio">

                        Portfolio

                    </a>

                </li>


                <li class="nav-item">

                    <a class="nav-link"
                       href="contact.html">

                        Contact

                    </a>

                </li>

            </ul>

        </div>

    </div>

</nav>



<!-- =====================================================
     PAGE HEADER
====================================================== -->

<header class="page-header text-center">

    <div class="container">

        <span class="badge bg-primary px-3 py-2 mb-3">

            <i class="bi bi-building me-1"></i>

            About Our Company

        </span>


        <h1>
            About XYZ Web Solutions
        </h1>


        <p class="lead mt-3">

            We create modern, responsive and
            business-focused digital solutions
            designed to help organizations grow online.

        </p>

    </div>

</header>



<!-- =====================================================
     ABOUT COMPANY
====================================================== -->

<section class="section-padding">

    <div class="container">

        <div class="row align-items-center g-5">


            <!-- IMAGE / GRAPHIC -->

            <div class="col-lg-6">

                <div class="about-image">

                    <i class="bi bi-laptop"></i>

                </div>

            </div>


            <!-- CONTENT -->

            <div class="col-lg-6">

                <span class="text-primary fw-semibold">
                    WHO WE ARE
                </span>


                <h2 class="section-title mt-2 mb-4">

                    Building Digital Experiences
                    That Work for Your Business

                </h2>


                <p>

                    XYZ Web Solutions is a web development
                    company focused on creating professional,
                    responsive and user-friendly websites
                    and web applications.

                </p>


                <p>

                    We work with businesses, startups,
                    professionals and organizations to
                    transform their ideas into reliable
                    digital experiences.

                </p>


                <p>

                    From a simple business website to a
                    custom web application, WordPress
                    platform or e-commerce store, our
                    approach focuses on clean development,
                    responsive design and maintainable code.

                </p>


                <a
                    href="contact.html"
                    class="btn btn-primary mt-3">

                    <i class="bi bi-chat-dots me-2"></i>

                    Discuss Your Project

                </a>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     MISSION & VISION
====================================================== -->

<section class="section-padding bg-white">

    <div class="container">

        <div class="text-center mb-5">

            <span class="text-primary fw-semibold">
                OUR DIRECTION
            </span>

            <h2 class="section-title mt-2">
                Mission & Vision
            </h2>

            <p class="section-subtitle mt-3">

                Our goal is to combine technology,
                usability and business requirements
                to create useful digital products.

            </p>

        </div>


        <div class="row g-4">


            <!-- MISSION -->

            <div class="col-md-6">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-bullseye"></i>

                    </div>


                    <h4>
                        Our Mission
                    </h4>


                    <p class="text-muted mb-0">

                        To provide practical and reliable
                        web solutions that help businesses
                        establish and improve their online
                        presence.

                    </p>

                </div>

            </div>


            <!-- VISION -->

            <div class="col-md-6">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-eye"></i>

                    </div>


                    <h4>
                        Our Vision
                    </h4>


                    <p class="text-muted mb-0">

                        To build long-term relationships with
                        clients by delivering quality digital
                        experiences and continuously improving
                        our technology and processes.

                    </p>

                </div>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     WHY CHOOSE US
====================================================== -->

<section class="section-padding">

    <div class="container">

        <div class="text-center mb-5">

            <span class="text-primary fw-semibold">
                WHAT WE FOCUS ON
            </span>

            <h2 class="section-title mt-2">
                Our Approach
            </h2>

        </div>


        <div class="row g-4">


            <!-- CARD 1 -->

            <div class="col-md-6 col-lg-3">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-phone"></i>

                    </div>


                    <h5>
                        Responsive Design
                    </h5>


                    <p class="text-muted mb-0">

                        Websites designed to work
                        across mobile, tablet and
                        desktop devices.

                    </p>

                </div>

            </div>


            <!-- CARD 2 -->

            <div class="col-md-6 col-lg-3">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-speedometer2"></i>

                    </div>


                    <h5>
                        Performance
                    </h5>


                    <p class="text-muted mb-0">

                        We focus on efficient code,
                        optimized assets and practical
                        website performance.

                    </p>

                </div>

            </div>


            <!-- CARD 3 -->

            <div class="col-md-6 col-lg-3">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-shield-check"></i>

                    </div>


                    <h5>
                        Security
                    </h5>


                    <p class="text-muted mb-0">

                        We consider common security
                        practices when developing
                        websites and applications.

                    </p>

                </div>

            </div>


            <!-- CARD 4 -->

            <div class="col-md-6 col-lg-3">

                <div class="feature-box">

                    <div class="feature-icon">

                        <i class="bi bi-code-square"></i>

                    </div>


                    <h5>
                        Clean Code
                    </h5>


                    <p class="text-muted mb-0">

                        Structured and maintainable
                        code makes future updates
                        easier.

                    </p>

                </div>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     OUR VALUES
====================================================== -->

<section class="section-padding bg-white">

    <div class="container">

        <div class="text-center mb-5">

            <span class="text-primary fw-semibold">
                OUR VALUES
            </span>

            <h2 class="section-title mt-2">
                Principles We Follow
            </h2>

        </div>


        <div class="row g-4">


            <!-- VALUE 1 -->

            <div class="col-md-6 col-lg-3">

                <div class="value-card text-center">

                    <i class="bi bi-people"></i>

                    <h5>
                        Collaboration
                    </h5>

                    <p class="text-muted mb-0">

                        We work closely with clients
                        to understand their requirements
                        and goals.

                    </p>

                </div>

            </div>


            <!-- VALUE 2 -->

            <div class="col-md-6 col-lg-3">

                <div class="value-card text-center">

                    <i class="bi bi-lightbulb"></i>

                    <h5>
                        Practical Innovation
                    </h5>

                    <p class="text-muted mb-0">

                        We use appropriate technologies
                        to solve real business problems.

                    </p>

                </div>

            </div>


            <!-- VALUE 3 -->

            <div class="col-md-6 col-lg-3">

                <div class="value-card text-center">

                    <i class="bi bi-check2-circle"></i>

                    <h5>
                        Quality
                    </h5>

                    <p class="text-muted mb-0">

                        We aim for reliable,
                        maintainable and usable
                        digital solutions.

                    </p>

                </div>

            </div>


            <!-- VALUE 4 -->

            <div class="col-md-6 col-lg-3">

                <div class="value-card text-center">

                    <i class="bi bi-headset"></i>

                    <h5>
                        Support
                    </h5>

                    <p class="text-muted mb-0">

                        We provide ongoing communication
                        and support for our projects.

                    </p>

                </div>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     TECHNOLOGIES
====================================================== -->

<section class="section-padding">

    <div class="container">

        <div class="text-center mb-5">

            <span class="text-primary fw-semibold">
                TECHNOLOGY
            </span>

            <h2 class="section-title mt-2">
                Technologies We Work With
            </h2>

            <p class="section-subtitle mt-3">

                We select technologies based on
                project requirements, scalability
                and maintainability.

            </p>

        </div>


        <div class="row g-3">


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-filetype-html"></i>

                    HTML5

                </div>

            </div>


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-filetype-css"></i>

                    CSS3

                </div>

            </div>


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-filetype-js"></i>

                    JavaScript

                </div>

            </div>


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-bootstrap"></i>

                    Bootstrap

                </div>

            </div>


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-wordpress"></i>

                    WordPress

                </div>

            </div>


            <div class="col-6 col-md-4 col-lg-2">

                <div class="technology">

                    <i class="bi bi-code-slash"></i>

                    PHP

                </div>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     DEVELOPMENT PROCESS
====================================================== -->

<section class="section-padding bg-white">

    <div class="container">

        <div class="text-center mb-5">

            <span class="text-primary fw-semibold">
                HOW WE WORK
            </span>

            <h2 class="section-title mt-2">
                Our Development Process
            </h2>

        </div>


        <div class="row g-4">


            <!-- STEP 1 -->

            <div class="col-md-6 col-lg-3">

                <div class="process-card">

                    <div class="process-number">
                        01
                    </div>

                    <h5>
                        Discover
                    </h5>

                    <p class="text-muted">

                        We understand your business,
                        audience, requirements and
                        project goals.

                    </p>

                </div>

            </div>


            <!-- STEP 2 -->

            <div class="col-md-6 col-lg-3">

                <div class="process-card">

                    <div class="process-number">
                        02
                    </div>

                    <h5>
                        Plan
                    </h5>

                    <p class="text-muted">

                        We define the website structure,
                        features, technology and
                        development approach.

                    </p>

                </div>

            </div>


            <!-- STEP 3 -->

            <div class="col-md-6 col-lg-3">

                <div class="process-card">

                    <div class="process-number">
                        03
                    </div>

                    <h5>
                        Develop
                    </h5>

                    <p class="text-muted">

                        We build and integrate the
                        required design, functionality
                        and content.

                    </p>

                </div>

            </div>


            <!-- STEP 4 -->

            <div class="col-md-6 col-lg-3">

                <div class="process-card">

                    <div class="process-number">
                        04
                    </div>

                    <h5>
                        Launch & Support
                    </h5>

                    <p class="text-muted">

                        After testing, we deploy the
                        project and provide support
                        for future improvements.

                    </p>

                </div>

            </div>

        </div>

    </div>

</section>



<!-- =====================================================
     CTA
====================================================== -->

<section class="section-padding cta-section">

    <div class="container text-center">

        <h2 class="fw-bold">
            Have a Project in Mind?
        </h2>

        <p class="lead mt-3 mb-4">

            Let's discuss your requirements and
            build a digital solution for your business.

        </p>


        <a
            href="contact.html"
            class="btn btn-primary btn-lg">

            <i class="bi bi-send me-2"></i>

            Contact Us

        </a>

    </div>

</section>



<!-- =====================================================
     FOOTER
====================================================== -->

<footer class="py-5">

    <div class="container">

        <div class="row g-4">


            <!-- COMPANY -->

            <div class="col-md-6 col-lg-4">

                <h5 class="text-white">
                    XYZ Web Solutions
                </h5>

                <p>

                    Professional website development,
                    WordPress, e-commerce and custom
                    web application solutions.

                </p>

            </div>


            <!-- QUICK LINKS -->

            <div class="col-md-6 col-lg-4">

                <h5 class="text-white">
                    Quick Links
                </h5>


                <ul class="list-unstyled">

                    <li class="mb-2">

                        <a href="index.html">
                            Home
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="index.html#services">
                            Services
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="about.html">
                            About
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="contact.html">
                            Contact
                        </a>

                    </li>

                </ul>

            </div>


            <!-- LEGAL -->

            <div class="col-md-6 col-lg-4">

                <h5 class="text-white">
                    Legal
                </h5>


                <ul class="list-unstyled">

                    <li class="mb-2">

                        <a href="privacy-policy.html">
                            Privacy Policy
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="terms.html">
                            Terms & Conditions
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="disclaimer.html">
                            Disclaimer
                        </a>

                    </li>


                    <li class="mb-2">

                        <a href="cookie-policy.html">
                            Cookie Policy
                        </a>

                    </li>

                </ul>

            </div>

        </div>


        <hr class="border-secondary my-4">


        <div class="text-center">

            <p class="mb-0">

                &copy; 2026 XYZ Web Solutions.
                All Rights Reserved.

            </p>

        </div>

    </div>

</footer>



<!-- =====================================================
     Bootstrap JS
====================================================== -->

<script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js">
</script>


</body>

</html>
```

## To add image

Absolutely. For your about.html, I’d make the image area a real accessible image with meaningful alt text, and add visible keyboard focus styles for links, buttons, form controls, and the navbar toggler.

1. Replace the current decorative image block

Replace:

<div class="about-image">
    <i class="bi bi-laptop"></i>
</div>

with:

<div class="about-image">
    <img
        src="images/about-web-development.jpg"
        alt="Web developer working on a responsive website and digital solution"
        class="img-fluid w-100 h-100 object-fit-cover"
        width="800"
        height="600">
</div>

If the image is purely decorative, use an empty alt instead:

<img
    src="images/about-web-development.jpg"
    alt=""
    class="img-fluid w-100 h-100 object-fit-cover"
    width="800"
    height="600">

2. Add accessible focus styles

Add this to your existing <style> section:

/* ================================================
   ACCESSIBILITY - KEYBOARD FOCUS
================================================= */

a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible,
.navbar-toggler:focus-visible {
    outline: 3px solid #ffc107;
    outline-offset: 3px;
}


/* Remove default outline only when
   the element is not keyboard-focused */

a:focus:not(:focus-visible),
button:focus:not(:focus-visible) {
    outline: none;
}


/* Make interactive elements easier to identify */

a,
button,
.nav-link {
    transition:
        color 0.2s ease,
        background-color 0.2s ease,
        border-color 0.2s ease,
        box-shadow 0.2s ease;
}


/* Skip link */

.skip-link {
    position: absolute;
    left: 10px;
    top: -100px;
    z-index: 9999;

    padding: 10px 16px;

    background: #212529;
    color: #fff;

    border-radius: 0 0 6px 6px;

    text-decoration: none;
    font-weight: 600;
}

.skip-link:focus {
    top: 0;
    color: #fff;
}

3. Add a skip-navigation link

Immediately after <body>:

<a href="#main-content" class="skip-link">
    Skip to main content
</a>

Then change your main content to:

<main id="main-content">

For example:

<body>

    <a href="#main-content" class="skip-link">
        Skip to main content
    </a>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        ...
    </nav>

    <header class="page-header text-center">
        ...
    </header>

    <main id="main-content">

        <!-- Page content -->

    </main>

    <footer>
        ...
    </footer>

</body>

4. Give decorative icons appropriate treatment

For icons that communicate information, keep them accessible with nearby text. For purely decorative icons, hide them from screen readers:

<i class="bi bi-laptop" aria-hidden="true"></i>

For example:

<a href="contact.html" class="btn btn-primary">
    <i class="bi bi-chat-dots me-2" aria-hidden="true"></i>
    Discuss Your Project
</a>

This prevents the screen reader from unnecessarily announcing the icon.

5. For social-media links

Because the icon itself is the link content, give it an accessible label:

<a
    href="#"
    aria-label="Visit our LinkedIn profile">

    <i class="bi bi-linkedin" aria-hidden="true"></i>

</a>

The same pattern works for Facebook, Instagram, GitHub, etc.

One important improvement: avoid using outline: none globally. Keyboard users need a clearly visible focus indicator. The :focus-visible approach above preserves a strong focus indicator for keyboard navigation without unnecessarily showing it for every mouse click.