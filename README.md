# basic-website-bootstrap-template

## Bootstrap index Page

Below is a complete single-file index.html for a modern web development company using Bootstrap 5.3.x, with no custom CSS or JavaScript files required. It includes a responsive navbar, hero, services, about, technologies, process, portfolio, testimonials, CTA, and footer.

```html
<!DOCTYPE html>
<html lang="en">

<head>

  <!-- =========================
       META
  ========================== -->

  <meta charset="UTF-8">

  <meta name="viewport"
        content="width=device-width, initial-scale=1">

  <meta name="description"
        content="Professional web development, WordPress, PHP, React, Next.js and e-commerce solutions for modern businesses.">

  <meta name="keywords"
        content="web development company, website development, WordPress development, PHP development, React development, Next.js, e-commerce">

  <meta name="author"
        content="XYZ Web Solutions">

  <meta name="robots"
        content="index, follow">

  <meta name="theme-color"
        content="#0d6efd">

  <title>XYZ Web Solutions | Web Development Company</title>


  <!-- =========================
       BOOTSTRAP 5.3
  ========================== -->

  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qK6kD0X4+0P4p1w5K2m5h3j9L6x0"
    crossorigin="anonymous">


  <!-- =========================
       BOOTSTRAP ICONS
  ========================== -->

  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">

</head>


<body>


  <!-- =====================================================
       NAVBAR
  ====================================================== -->

  <nav class="navbar navbar-expand-lg bg-white border-bottom sticky-top">

    <div class="container">

      <!-- Logo -->

      <a class="navbar-brand fw-bold fs-4"
         href="index.html">

        <i class="bi bi-code-slash text-primary"></i>

        XYZ<span class="text-primary">Web</span>

      </a>


      <!-- Mobile Toggle -->

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


      <!-- Navigation -->

      <div class="collapse navbar-collapse"
           id="mainNavbar">

        <ul class="navbar-nav ms-auto align-items-lg-center gap-lg-2">

          <li class="nav-item">

            <a class="nav-link active"
               href="#home">

              Home

            </a>

          </li>


          <li class="nav-item">

            <a class="nav-link"
               href="#services">

              Services

            </a>

          </li>


          <li class="nav-item">

            <a class="nav-link"
               href="#about">

              About

            </a>

          </li>


          <li class="nav-item">

            <a class="nav-link"
               href="#portfolio">

              Portfolio

            </a>

          </li>


          <li class="nav-item">

            <a class="nav-link"
               href="#process">

              Process

            </a>

          </li>


          <li class="nav-item">

            <a class="nav-link"
               href="#contact">

              Contact

            </a>

          </li>


          <li class="nav-item ms-lg-2">

            <a class="btn btn-primary px-4"
               href="#contact">

              Get Started

            </a>

          </li>

        </ul>

      </div>

    </div>

  </nav>



  <!-- =====================================================
       HERO
  ====================================================== -->

  <main id="home">

    <section class="bg-dark text-white py-5">

      <div class="container">

        <div class="row align-items-center min-vh-75 py-5">


          <!-- Hero Content -->

          <div class="col-lg-7">

            <span class="badge text-bg-primary mb-3 px-3 py-2">

              <i class="bi bi-stars"></i>

              Digital Solutions for Modern Businesses

            </span>


            <h1 class="display-3 fw-bold lh-1 mb-4">

              We Build
              <span class="text-primary">
                Powerful Websites
              </span>
              That Grow Your Business.

            </h1>


            <p class="lead text-white-50 mb-4">

              We design and develop fast, secure, responsive and
              conversion-focused websites and web applications using
              modern technologies.

            </p>


            <div class="d-flex flex-wrap gap-3">

              <a href="#contact"
                 class="btn btn-primary btn-lg px-4">

                Start Your Project

                <i class="bi bi-arrow-right ms-2"></i>

              </a>


              <a href="#portfolio"
                 class="btn btn-outline-light btn-lg px-4">

                View Portfolio

              </a>

            </div>


            <!-- Trust Points -->

            <div class="row mt-5 g-3">

              <div class="col-sm-4">

                <div class="d-flex align-items-center">

                  <i class="bi bi-check-circle-fill text-primary fs-4 me-2"></i>

                  <span>Responsive</span>

                </div>

              </div>


              <div class="col-sm-4">

                <div class="d-flex align-items-center">

                  <i class="bi bi-check-circle-fill text-primary fs-4 me-2"></i>

                  <span>SEO Friendly</span>

                </div>

              </div>


              <div class="col-sm-4">

                <div class="d-flex align-items-center">

                  <i class="bi bi-check-circle-fill text-primary fs-4 me-2"></i>

                  <span>Secure</span>

                </div>

              </div>

            </div>

          </div>


          <!-- Hero Visual -->

          <div class="col-lg-5 mt-5 mt-lg-0">

            <div class="card bg-primary border-0 shadow-lg">

              <div class="card-body p-4">


                <div class="bg-dark rounded-3 p-4">


                  <div class="d-flex gap-2 mb-4">

                    <span class="rounded-circle bg-danger"
                          style="width:12px;height:12px;"></span>

                    <span class="rounded-circle bg-warning"
                          style="width:12px;height:12px;"></span>

                    <span class="rounded-circle bg-success"
                          style="width:12px;height:12px;"></span>

                  </div>


                  <div class="font-monospace small">

                    <div class="text-secondary">
                      &lt;website&gt;
                    </div>

                    <div class="text-info ms-3">
                      &lt;header&gt;
                    </div>

                    <div class="text-success ms-4">
                      Your Business
                    </div>

                    <div class="text-info ms-3">
                      &lt;/header&gt;
                    </div>

                    <div class="text-warning ms-3">
                      &lt;main&gt;
                    </div>

                    <div class="text-primary ms-4">
                      Digital Growth
                    </div>

                    <div class="text-warning ms-3">
                      &lt;/main&gt;
                    </div>

                    <div class="text-secondary">
                      &lt;/website&gt;
                    </div>

                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         SERVICES
    ====================================================== -->

    <section id="services"
             class="py-5">

      <div class="container py-5">

        <div class="text-center mb-5">

          <span class="text-primary fw-semibold">
            WHAT WE DO
          </span>

          <h2 class="display-6 fw-bold mt-2">
            Our Services
          </h2>

          <p class="text-secondary mx-auto"
             style="max-width:650px;">

            From simple business websites to complex web
            applications, we provide complete digital solutions.

          </p>

        </div>


        <div class="row g-4">


          <!-- Service 1 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-window-stack fs-3"></i>

                </div>

                <h3 class="h4">
                  Website Development
                </h3>

                <p class="text-secondary">

                  Modern, responsive and high-performance
                  websites designed around your business goals.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>


          <!-- Service 2 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-wordpress fs-3"></i>

                </div>

                <h3 class="h4">
                  WordPress Development
                </h3>

                <p class="text-secondary">

                  Professional WordPress websites,
                  custom themes, plugins and business solutions.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>


          <!-- Service 3 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-code-square fs-3"></i>

                </div>

                <h3 class="h4">
                  Custom Web Applications
                </h3>

                <p class="text-secondary">

                  Scalable web applications built with
                  modern frameworks and backend technologies.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>


          <!-- Service 4 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-cart3 fs-3"></i>

                </div>

                <h3 class="h4">
                  E-Commerce Development
                </h3>

                <p class="text-secondary">

                  Powerful online stores with secure checkout,
                  product management and payment integration.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>


          <!-- Service 5 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-diagram-3 fs-3"></i>

                </div>

                <h3 class="h4">
                  API Development
                </h3>

                <p class="text-secondary">

                  Reliable REST APIs and third-party integrations
                  connecting your applications and services.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>


          <!-- Service 6 -->

          <div class="col-md-6 col-lg-4">

            <div class="card h-100 border-0 shadow-sm">

              <div class="card-body p-4">

                <div class="bg-primary-subtle text-primary
                            rounded-3 d-inline-flex p-3 mb-4">

                  <i class="bi bi-speedometer2 fs-3"></i>

                </div>

                <h3 class="h4">
                  Maintenance & Support
                </h3>

                <p class="text-secondary">

                  Ongoing updates, security, performance
                  optimization and technical support.

                </p>

                <a href="#contact"
                   class="text-decoration-none">

                  Learn More
                  <i class="bi bi-arrow-right"></i>

                </a>

              </div>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         ABOUT
    ====================================================== -->

    <section id="about"
             class="bg-light py-5">

      <div class="container py-5">

        <div class="row align-items-center g-5">


          <div class="col-lg-6">

            <span class="text-primary fw-semibold">
              ABOUT US
            </span>

            <h2 class="display-6 fw-bold mt-2">
              Technology That Helps Your Business Move Forward.
            </h2>

            <p class="text-secondary lead mt-4">

              We are a web development company focused on creating
              reliable, scalable and user-friendly digital products.

            </p>

            <p class="text-secondary">

              Our team combines modern design, development,
              performance optimization and business thinking to
              create websites and applications that provide real
              value to businesses.

            </p>


            <div class="row mt-4 g-3">

              <div class="col-6">

                <div class="border rounded-3 p-3 bg-white">

                  <h3 class="fw-bold mb-1">
                    100+
                  </h3>

                  <small class="text-secondary">
                    Projects
                  </small>

                </div>

              </div>


              <div class="col-6">

                <div class="border rounded-3 p-3 bg-white">

                  <h3 class="fw-bold mb-1">
                    5+
                  </h3>

                  <small class="text-secondary">
                    Years Experience
                  </small>

                </div>

              </div>

            </div>

          </div>


          <div class="col-lg-6">

            <div class="row g-3">

              <div class="col-6">

                <div class="card border-0 shadow-sm text-center p-4">

                  <i class="bi bi-phone text-primary display-5"></i>

                  <h3 class="h5 mt-3">
                    Responsive
                  </h3>

                  <p class="small text-secondary mb-0">
                    Mobile-first experiences
                  </p>

                </div>

              </div>


              <div class="col-6">

                <div class="card border-0 shadow-sm text-center p-4">

                  <i class="bi bi-shield-check text-primary display-5"></i>

                  <h3 class="h5 mt-3">
                    Secure
                  </h3>

                  <p class="small text-secondary mb-0">
                    Security-focused development
                  </p>

                </div>

              </div>


              <div class="col-6">

                <div class="card border-0 shadow-sm text-center p-4">

                  <i class="bi bi-lightning-charge text-primary display-5"></i>

                  <h3 class="h5 mt-3">
                    Fast
                  </h3>

                  <p class="small text-secondary mb-0">
                    Performance optimized
                  </p>

                </div>

              </div>


              <div class="col-6">

                <div class="card border-0 shadow-sm text-center p-4">

                  <i class="bi bi-search text-primary display-5"></i>

                  <h3 class="h5 mt-3">
                    SEO Ready
                  </h3>

                  <p class="small text-secondary mb-0">
                    Search-friendly structure
                  </p>

                </div>

              </div>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         TECHNOLOGIES
    ====================================================== -->

    <section class="py-5">

      <div class="container py-5">

        <div class="text-center mb-5">

          <span class="text-primary fw-semibold">
            TECHNOLOGIES
          </span>

          <h2 class="display-6 fw-bold mt-2">
            Technologies We Work With
          </h2>

        </div>


        <div class="row g-3 justify-content-center text-center">

          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-filetype-html fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                HTML5
              </h3>

            </div>

          </div>


          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-filetype-css fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                CSS3
              </h3>

            </div>

          </div>


          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-filetype-js fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                JavaScript
              </h3>

            </div>

          </div>


          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-bootstrap fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                Bootstrap
              </h3>

            </div>

          </div>


          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-wordpress fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                WordPress
              </h3>

            </div>

          </div>


          <div class="col-6 col-md-4 col-lg-2">

            <div class="border rounded-3 p-4">

              <i class="bi bi-braces fs-1 text-primary"></i>

              <h3 class="h6 mt-3 mb-0">
                PHP
              </h3>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         PROCESS
    ====================================================== -->

    <section id="process"
             class="bg-dark text-white py-5">

      <div class="container py-5">

        <div class="text-center mb-5">

          <span class="text-primary fw-semibold">
            HOW WE WORK
          </span>

          <h2 class="display-6 fw-bold mt-2">
            Our Development Process
          </h2>

        </div>


        <div class="row g-4">


          <div class="col-md-6 col-lg-3">

            <div class="text-center">

              <div class="bg-primary rounded-circle
                          d-inline-flex align-items-center
                          justify-content-center mb-4"
                   style="width:70px;height:70px;">

                <span class="fs-4 fw-bold">
                  01
                </span>

              </div>

              <h3 class="h4">
                Discover
              </h3>

              <p class="text-white-50">
                We understand your business, goals,
                audience and project requirements.
              </p>

            </div>

          </div>


          <div class="col-md-6 col-lg-3">

            <div class="text-center">

              <div class="bg-primary rounded-circle
                          d-inline-flex align-items-center
                          justify-content-center mb-4"
                   style="width:70px;height:70px;">

                <span class="fs-4 fw-bold">
                  02
                </span>

              </div>

              <h3 class="h4">
                Design
              </h3>

              <p class="text-white-50">
                We create intuitive layouts and experiences
                aligned with your brand.
              </p>

            </div>

          </div>


          <div class="col-md-6 col-lg-3">

            <div class="text-center">

              <div class="bg-primary rounded-circle
                          d-inline-flex align-items-center
                          justify-content-center mb-4"
                   style="width:70px;height:70px;">

                <span class="fs-4 fw-bold">
                  03
                </span>

              </div>

              <h3 class="h4">
                Develop
              </h3>

              <p class="text-white-50">
                Our developers build and test the
                website using modern technologies.
              </p>

            </div>

          </div>


          <div class="col-md-6 col-lg-3">

            <div class="text-center">

              <div class="bg-primary rounded-circle
                          d-inline-flex align-items-center
                          justify-content-center mb-4"
                   style="width:70px;height:70px;">

                <span class="fs-4 fw-bold">
                  04
                </span>

              </div>

              <h3 class="h4">
                Launch
              </h3>

              <p class="text-white-50">
                After testing and approval, we deploy
                your website and provide support.
              </p>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         PORTFOLIO
    ====================================================== -->

    <section id="portfolio"
             class="py-5">

      <div class="container py-5">

        <div class="text-center mb-5">

          <span class="text-primary fw-semibold">
            OUR WORK
          </span>

          <h2 class="display-6 fw-bold mt-2">
            Featured Projects
          </h2>

        </div>


        <div class="row g-4">


          <div class="col-md-6 col-lg-4">

            <div class="card border-0 shadow-sm overflow-hidden">

              <div class="bg-primary-subtle"
                   style="height:220px;">

                <div class="h-100 d-flex
                            align-items-center
                            justify-content-center">

                  <i class="bi bi-shop display-1 text-primary"></i>

                </div>

              </div>

              <div class="card-body p-4">

                <span class="badge text-bg-primary">
                  E-Commerce
                </span>

                <h3 class="h4 mt-3">
                  Online Store
                </h3>

                <p class="text-secondary">
                  Modern e-commerce solution with
                  product and order management.
                </p>

              </div>

            </div>

          </div>


          <div class="col-md-6 col-lg-4">

            <div class="card border-0 shadow-sm overflow-hidden">

              <div class="bg-success-subtle"
                   style="height:220px;">

                <div class="h-100 d-flex
                            align-items-center
                            justify-content-center">

                  <i class="bi bi-building display-1 text-success"></i>

                </div>

              </div>

              <div class="card-body p-4">

                <span class="badge text-bg-success">
                  Corporate
                </span>

                <h3 class="h4 mt-3">
                  Business Website
                </h3>

                <p class="text-secondary">
                  Professional corporate website
                  designed for business growth.
                </p>

              </div>

            </div>

          </div>


          <div class="col-md-6 col-lg-4">

            <div class="card border-0 shadow-sm overflow-hidden">

              <div class="bg-warning-subtle"
                   style="height:220px;">

                <div class="h-100 d-flex
                            align-items-center
                            justify-content-center">

                  <i class="bi bi-bar-chart-line display-1 text-warning"></i>

                </div>

              </div>

              <div class="card-body p-4">

                <span class="badge text-bg-warning">
                  Web Application
                </span>

                <h3 class="h4 mt-3">
                  Business Dashboard
                </h3>

                <p class="text-secondary">
                  Data-driven dashboard for managing
                  business operations.
                </p>

              </div>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         TESTIMONIALS
    ====================================================== -->

    <section class="bg-light py-5">

      <div class="container py-5">

        <div class="text-center mb-5">

          <span class="text-primary fw-semibold">
            CLIENT FEEDBACK
          </span>

          <h2 class="display-6 fw-bold mt-2">
            What Our Clients Say
          </h2>

        </div>


        <div class="row g-4">


          <div class="col-md-4">

            <div class="card border-0 shadow-sm h-100">

              <div class="card-body p-4">

                <div class="text-warning mb-3">

                  ★★★★★

                </div>

                <p class="text-secondary">

                  "The team understood our requirements and
                  delivered a clean, professional website."

                </p>

                <h3 class="h6 mb-1">
                  Rahul Sharma
                </h3>

                <small class="text-secondary">
                  Business Owner
                </small>

              </div>

            </div>

          </div>


          <div class="col-md-4">

            <div class="card border-0 shadow-sm h-100">

              <div class="card-body p-4">

                <div class="text-warning mb-3">

                  ★★★★★

                </div>

                <p class="text-secondary">

                  "Excellent communication and a smooth
                  development process from start to finish."

                </p>

                <h3 class="h6 mb-1">
                  Priya Patel
                </h3>

                <small class="text-secondary">
                  Founder
                </small>

              </div>

            </div>

          </div>


          <div class="col-md-4">

            <div class="card border-0 shadow-sm h-100">

              <div class="card-body p-4">

                <div class="text-warning mb-3">

                  ★★★★★

                </div>

                <p class="text-secondary">

                  "Our new website is faster, easier to manage
                  and works perfectly on mobile devices."

                </p>

                <h3 class="h6 mb-1">
                  Amit Mehta
                </h3>

                <small class="text-secondary">
                  Director
                </small>

              </div>

            </div>

          </div>

        </div>

      </div>

    </section>



    <!-- =====================================================
         CTA
    ====================================================== -->

    <section id="contact"
             class="py-5">

      <div class="container py-5">

        <div class="bg-primary text-white rounded-4
                    p-4 p-md-5 text-center">

          <h2 class="display-6 fw-bold">
            Have a Project in Mind?
          </h2>

          <p class="lead mt-3 mb-4">

            Let's turn your idea into a modern,
            high-performing digital experience.

          </p>

          <a href="mailto:info@example.com"
             class="btn btn-light btn-lg px-4">

            <i class="bi bi-envelope me-2"></i>

            Start a Conversation

          </a>

        </div>

      </div>

    </section>

  </main>



  <!-- =====================================================
       FOOTER
  ====================================================== -->

  <footer class="bg-dark text-white pt-5">

    <div class="container">

      <div class="row g-4 pb-5">


        <!-- Company -->

        <div class="col-lg-4">

          <a href="index.html"
             class="text-white text-decoration-none">

            <h2 class="h4 fw-bold">

              <i class="bi bi-code-slash text-primary"></i>

              XYZ<span class="text-primary">Web</span>

            </h2>

          </a>

          <p class="text-white-50 mt-3">

            We build modern websites and web applications
            that help businesses establish and grow their
            digital presence.

          </p>


          <div class="d-flex gap-3">

            <a href="#"
               class="text-white fs-5"
               aria-label="Facebook">

              <i class="bi bi-facebook"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="Instagram">

              <i class="bi bi-instagram"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="LinkedIn">

              <i class="bi bi-linkedin"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="GitHub">

              <i class="bi bi-github"></i>

            </a>

          </div>

        </div>


        <!-- Services -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Services
          </h3>

          <ul class="list-unstyled">

            <li class="mb-2">
              <a href="#services"
                 class="text-white-50 text-decoration-none">
                Web Development
              </a>
            </li>

            <li class="mb-2">
              <a href="#services"
                 class="text-white-50 text-decoration-none">
                WordPress
              </a>
            </li>

            <li class="mb-2">
              <a href="#services"
                 class="text-white-50 text-decoration-none">
                E-Commerce
              </a>
            </li>

            <li class="mb-2">
              <a href="#services"
                 class="text-white-50 text-decoration-none">
                API Development
              </a>
            </li>

          </ul>

        </div>


        <!-- Company Links -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Company
          </h3>

          <ul class="list-unstyled">

            <li class="mb-2">
              <a href="#about"
                 class="text-white-50 text-decoration-none">
                About
              </a>
            </li>

            <li class="mb-2">
              <a href="#portfolio"
                 class="text-white-50 text-decoration-none">
                Portfolio
              </a>
            </li>

            <li class="mb-2">
              <a href="#process"
                 class="text-white-50 text-decoration-none">
                Process
              </a>
            </li>

            <li class="mb-2">
              <a href="#contact"
                 class="text-white-50 text-decoration-none">
                Contact
              </a>
            </li>

          </ul>

        </div>


        <!-- Legal -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Legal
          </h3>

          <ul class="list-unstyled">

            <li class="mb-2">
              <a href="privacy-policy.html"
                 class="text-white-50 text-decoration-none">
                Privacy Policy
              </a>
            </li>

            <li class="mb-2">
              <a href="terms.html"
                 class="text-white-50 text-decoration-none">
                Terms &amp; Conditions
              </a>
            </li>

            <li class="mb-2">
              <a href="disclaimer.html"
                 class="text-white-50 text-decoration-none">
                Disclaimer
              </a>
            </li>

            <li class="mb-2">
              <a href="cookie-policy.html"
                 class="text-white-50 text-decoration-none">
                Cookie Policy
              </a>
            </li>

          </ul>

        </div>


        <!-- Contact -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Contact
          </h3>

          <ul class="list-unstyled text-white-50">

            <li class="mb-2">

              <i class="bi bi-envelope me-2"></i>

              info@example.com

            </li>

            <li class="mb-2">

              <i class="bi bi-telephone me-2"></i>

              +91 XXXXX XXXXX

            </li>

            <li>

              <i class="bi bi-geo-alt me-2"></i>

              India

            </li>

          </ul>

        </div>

      </div>


      <!-- Copyright -->

      <div class="border-top border-secondary
                  py-4 text-center">

        <p class="text-white-50 mb-0">

          &copy; 2026 XYZ Web Solutions.
          All Rights Reserved.

        </p>

      </div>

    </div>

  </footer>



  <!-- =====================================================
       BOOTSTRAP JAVASCRIPT
  ====================================================== -->

  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ndDqU0Gzau9qJ1lfW4h5w5F5P5P5x5W5G5R5k5k5k5k5k5k5"
    crossorigin="anonymous">
  </script>

</body>

</html>
```

Note: The Bootstrap CDN URLs above are intended to use Bootstrap 5.3.x. For production, use the official Bootstrap CDN snippet for the exact release you choose rather than relying on a copied integrity hash.

The page is structured so you can later split it into:

```
index.html
services.html
about.html
portfolio.html
contact.html
privacy-policy.html
terms.html
disclaimer.html
cookie-policy.html
```

and the sections can also be converted directly into a PHP/WordPress theme later.


## 🛸 animated Page 404 with Flying ufo

Here’s a complete responsive animated 404 page using only HTML + CSS. It includes a floating 404 number, animated stars, a moving astronaut/planet-style illustration, and a button back to the homepage.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">

  <meta name="description"
        content="404 - Page Not Found">

  <title>404 - Page Not Found</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;

      font-family: Arial, Helvetica, sans-serif;

      background:
        radial-gradient(circle at 50% 40%,
          #26356f 0%,
          #101735 45%,
          #050816 100%);

      color: #fff;
    }

    /* =========================
       SPACE BACKGROUND
    ========================= */

    .space {
      position: fixed;
      inset: 0;
      overflow: hidden;
      pointer-events: none;
    }

    .star {
      position: absolute;
      width: 3px;
      height: 3px;
      background: #fff;
      border-radius: 50%;

      animation:
        twinkle 2s infinite ease-in-out,
        moveStars 12s linear infinite;
    }

    .star:nth-child(1) {
      top: 15%;
      left: 10%;
      animation-delay: .2s;
    }

    .star:nth-child(2) {
      top: 30%;
      left: 25%;
      animation-delay: .8s;
    }

    .star:nth-child(3) {
      top: 12%;
      left: 75%;
      animation-delay: 1.2s;
    }

    .star:nth-child(4) {
      top: 70%;
      left: 15%;
      animation-delay: .5s;
    }

    .star:nth-child(5) {
      top: 80%;
      left: 80%;
      animation-delay: 1.5s;
    }

    .star:nth-child(6) {
      top: 55%;
      left: 90%;
      animation-delay: .9s;
    }

    .star:nth-child(7) {
      top: 20%;
      left: 50%;
      animation-delay: 1.8s;
    }

    .star:nth-child(8) {
      top: 85%;
      left: 45%;
      animation-delay: .3s;
    }

    .star:nth-child(9) {
      top: 45%;
      left: 5%;
      animation-delay: 1s;
    }

    .star:nth-child(10) {
      top: 60%;
      left: 65%;
      animation-delay: 1.4s;
    }

    @keyframes twinkle {
      0%, 100% {
        opacity: .2;
        transform: scale(.6);
      }

      50% {
        opacity: 1;
        transform: scale(1.5);
      }
    }

    @keyframes moveStars {
      0% {
        margin-top: 0;
      }

      50% {
        margin-top: -15px;
      }

      100% {
        margin-top: 0;
      }
    }


    /* =========================
       MAIN CONTAINER
    ========================= */

    .error-page {
      position: relative;
      z-index: 2;

      width: 90%;
      max-width: 850px;

      text-align: center;

      padding: 40px 20px;
    }


    /* =========================
       404 NUMBER
    ========================= */

    .error-number {
      position: relative;

      font-size: clamp(120px, 25vw, 280px);

      font-weight: 900;
      line-height: .8;

      letter-spacing: -15px;

      color: transparent;

      background: linear-gradient(
        180deg,
        #ffffff,
        #7d8cff,
        #4754c7
      );

      -webkit-background-clip: text;
      background-clip: text;

      text-shadow:
        0 15px 40px rgba(0, 0, 0, .35);

      animation: float404 4s ease-in-out infinite;
    }

    @keyframes float404 {
      0%, 100% {
        transform: translateY(0);
      }

      50% {
        transform: translateY(-18px);
      }
    }


    /* =========================
       PLANET
    ========================= */

    .planet {
      position: absolute;

      width: 90px;
      height: 90px;

      right: 10%;
      top: 15%;

      border-radius: 50%;

      background:
        radial-gradient(
          circle at 30% 30%,
          #ffdf8a,
          #ff9e4a 45%,
          #c94e62 75%,
          #642b72
        );

      box-shadow:
        0 0 30px rgba(255, 173, 82, .5);

      animation: planetFloat 5s ease-in-out infinite;
    }

    .planet::after {
      content: "";

      position: absolute;

      width: 135px;
      height: 35px;

      border: 5px solid rgba(255,255,255,.65);

      border-radius: 50%;

      left: -22px;
      top: 28px;

      transform: rotate(-18deg);
    }

    @keyframes planetFloat {
      0%, 100% {
        transform: translateY(0) rotate(0);
      }

      50% {
        transform: translateY(-25px) rotate(8deg);
      }
    }


    /* =========================
       TEXT
    ========================= */

    h1 {
      margin-top: 45px;

      font-size: clamp(28px, 5vw, 48px);

      font-weight: 700;

      animation: fadeUp 1s ease forwards;
    }

    .message {
      max-width: 600px;

      margin: 15px auto 0;

      color: #c6cbea;

      font-size: 18px;

      line-height: 1.7;

      animation: fadeUp 1.3s ease forwards;
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(25px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }


    /* =========================
       BUTTON
    ========================= */

    .home-btn {
      display: inline-flex;

      margin-top: 30px;

      padding: 14px 28px;

      border-radius: 50px;

      color: #fff;

      text-decoration: none;

      font-size: 16px;
      font-weight: 600;

      background: linear-gradient(
        135deg,
        #6c63ff,
        #8b5cf6
      );

      box-shadow:
        0 10px 30px rgba(108, 99, 255, .35);

      transition:
        transform .3s ease,
        box-shadow .3s ease;
    }

    .home-btn:hover {
      transform: translateY(-5px) scale(1.03);

      box-shadow:
        0 15px 40px rgba(108, 99, 255, .55);
    }


    /* =========================
       UFO
    ========================= */

    .ufo {
      position: absolute;

      left: 8%;
      top: 25%;

      width: 85px;
      height: 35px;

      background: #8d96ff;

      border-radius: 50%;

      box-shadow:
        0 0 25px #7c83ff;

      animation: ufoMove 7s ease-in-out infinite;
    }

    .ufo::before {
      content: "";

      position: absolute;

      width: 40px;
      height: 25px;

      left: 22px;
      top: -14px;

      border-radius: 50% 50% 20% 20%;

      background: #b9c0ff;
    }

    .ufo::after {
      content: "";

      position: absolute;

      width: 55px;
      height: 12px;

      left: 15px;
      bottom: -8px;

      background: rgba(112, 255, 230, .45);

      filter: blur(4px);

      border-radius: 50%;
    }

    @keyframes ufoMove {
      0% {
        transform: translate(0, 0) rotate(-5deg);
      }

      25% {
        transform: translate(50px, -25px) rotate(5deg);
      }

      50% {
        transform: translate(100px, 0) rotate(-5deg);
      }

      75% {
        transform: translate(50px, 25px) rotate(5deg);
      }

      100% {
        transform: translate(0, 0) rotate(-5deg);
      }
    }


    /* =========================
       RESPONSIVE
    ========================= */

    @media (max-width: 600px) {

      .error-page {
        padding: 20px;
      }

      .error-number {
        letter-spacing: -8px;
      }

      .message {
        font-size: 16px;
      }

      .planet {
        width: 55px;
        height: 55px;

        right: 3%;
        top: 12%;
      }

      .planet::after {
        width: 85px;
        height: 25px;

        left: -15px;
        top: 15px;
      }

      .ufo {
        transform: scale(.7);
        left: 2%;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      *,
      *::before,
      *::after {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        scroll-behavior: auto !important;
      }
    }
  </style>
</head>

<body>

  <!-- Animated Background -->
  <div class="space">

    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>
    <span class="star"></span>

  </div>


  <!-- Floating Planet -->
  <div class="planet"></div>


  <!-- Flying UFO -->
  <div class="ufo"></div>


  <!-- 404 Content -->
  <main class="error-page">

    <div class="error-number">
      404
    </div>

    <h1>
      Page Not Found
    </h1>

    <p class="message">
      Oops! The page you're looking for seems to have
      disappeared into space. Don't worry, let's get you
      back to somewhere familiar.
    </p>

    <a href="/" class="home-btn">
      ← Back to Home
    </a>

  </main>

</body>
</html>
```

What this includes

🌌 Animated space background

✨ Twinkling stars

🪐 Floating animated planet

🛸 Flying UFO

Animated 404 typography

Fade-in heading and message

Hover animation on the Home button

Fully responsive mobile layout

prefers-reduced-motion accessibility support

No JavaScript or external libraries required


You can save it directly as 404.html and open it in the browser.

## broken Link 404 error-page

Absolutely — a broken-link / snapped-chain style fits a 404 page better. Here is a version where the broken link visually separates, shakes, and reconnects with a subtle animated effect.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>404 - Broken Link</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;

      font-family: Arial, Helvetica, sans-serif;

      background: #f5f7fb;
      color: #1d2433;

      overflow: hidden;
    }

    .error-page {
      width: 90%;
      max-width: 700px;
      text-align: center;
    }

    /* =========================
       BROKEN LINK
    ========================= */

    .broken-link {
      position: relative;

      width: 280px;
      height: 150px;

      margin: 0 auto 20px;

      display: flex;
      align-items: center;
      justify-content: center;
    }

    .link {
      position: absolute;

      width: 125px;
      height: 55px;

      border: 12px solid #4f46e5;
      border-radius: 40px;

      transform: rotate(-35deg);

      animation: linkFloat 3s ease-in-out infinite;
    }

    .link-left {
      left: 25px;
    }

    .link-right {
      right: 25px;

      border-color: #8b5cf6;

      transform: rotate(-35deg);
      animation:
        linkFloatRight 3s ease-in-out infinite,
        brokenShake 2s ease-in-out infinite;
    }

    /* Hide the inner part to make it look like a chain */
    .link::after {
      content: "";

      position: absolute;

      width: 80px;
      height: 35px;

      background: #f5f7fb;

      border-radius: 30px;

      top: -2px;
      left: 10px;
    }

    /* Gap between broken links */
    .gap {
      position: absolute;

      width: 55px;
      height: 8px;

      background: #f5f7fb;

      z-index: 5;

      transform: rotate(-35deg);
    }

    /* Small broken pieces */
    .piece {
      position: absolute;

      width: 12px;
      height: 12px;

      border-radius: 50%;

      background: #6366f1;

      opacity: 0;

      animation: pieces 2.5s ease-in-out infinite;
    }

    .piece:nth-child(1) {
      left: 105px;
      top: 45px;
      animation-delay: .1s;
    }

    .piece:nth-child(2) {
      left: 145px;
      top: 70px;
      animation-delay: .5s;
    }

    .piece:nth-child(3) {
      left: 125px;
      top: 90px;
      animation-delay: .9s;
    }

    /* =========================
       ANIMATIONS
    ========================= */

    @keyframes linkFloat {
      0%, 100% {
        transform: translateX(0) rotate(-35deg);
      }

      50% {
        transform: translateX(-10px) rotate(-38deg);
      }
    }

    @keyframes linkFloatRight {
      0%, 100% {
        transform: translateX(0) rotate(-35deg);
      }

      50% {
        transform: translateX(10px) rotate(-32deg);
      }
    }

    @keyframes brokenShake {
      0%, 100% {
        filter: none;
      }

      48% {
        filter: none;
      }

      50% {
        filter: drop-shadow(0 0 8px rgba(99,102,241,.5));
      }

      52% {
        filter: none;
      }
    }

    @keyframes pieces {
      0% {
        opacity: 0;
        transform: translate(0, 0) scale(.3);
      }

      25% {
        opacity: 1;
      }

      100% {
        opacity: 0;
        transform: translateY(35px) scale(1);
      }
    }


    /* =========================
       404 NUMBER
    ========================= */

    .error-code {
      font-size: clamp(80px, 18vw, 150px);

      line-height: 1;

      font-weight: 900;

      color: #1f2937;

      letter-spacing: -8px;

      animation: codeFloat 4s ease-in-out infinite;
    }

    .error-code span {
      color: #6366f1;
    }

    @keyframes codeFloat {
      0%, 100% {
        transform: translateY(0);
      }

      50% {
        transform: translateY(-8px);
      }
    }


    /* =========================
       TEXT
    ========================= */

    h1 {
      margin-top: 15px;

      font-size: clamp(28px, 5vw, 42px);
    }

    .description {
      max-width: 500px;

      margin: 15px auto 0;

      color: #6b7280;

      font-size: 17px;

      line-height: 1.7;
    }


    /* =========================
       BUTTON
    ========================= */

    .home-button {
      display: inline-block;

      margin-top: 28px;

      padding: 14px 30px;

      background: #4f46e5;

      color: #fff;

      text-decoration: none;

      border-radius: 8px;

      font-weight: 600;

      transition:
        transform .3s ease,
        box-shadow .3s ease,
        background .3s ease;
    }

    .home-button:hover {
      background: #4338ca;

      transform: translateY(-4px);

      box-shadow:
        0 12px 25px rgba(79, 70, 229, .25);
    }


    /* =========================
       DECORATIVE DASHES
    ========================= */

    .dash {
      position: absolute;

      width: 7px;
      height: 7px;

      border-radius: 50%;

      background: #a5b4fc;

      animation: dashFloat 3s ease-in-out infinite;
    }

    .dash.one {
      top: 20%;
      left: 15%;
    }

    .dash.two {
      top: 70%;
      left: 12%;

      animation-delay: .7s;
    }

    .dash.three {
      top: 25%;
      right: 15%;

      animation-delay: 1.2s;
    }

    .dash.four {
      bottom: 15%;
      right: 18%;

      animation-delay: .4s;
    }

    @keyframes dashFloat {
      0%, 100% {
        transform: translateY(0);
        opacity: .4;
      }

      50% {
        transform: translateY(-15px);
        opacity: 1;
      }
    }


    /* =========================
       MOBILE
    ========================= */

    @media (max-width: 600px) {

      .broken-link {
        transform: scale(.8);
        margin-bottom: 0;
      }

      .error-code {
        letter-spacing: -5px;
      }

      .description {
        font-size: 15px;
      }
    }


    /* =========================
       REDUCE MOTION
    ========================= */

    @media (prefers-reduced-motion: reduce) {

      *,
      *::before,
      *::after {
        animation: none !important;
      }
    }
  </style>
</head>

<body>

  <!-- Decorative elements -->
  <span class="dash one"></span>
  <span class="dash two"></span>
  <span class="dash three"></span>
  <span class="dash four"></span>


  <main class="error-page">

    <!-- Broken Link Animation -->
    <div class="broken-link">

      <div class="link link-left"></div>

      <div class="gap"></div>

      <div class="link link-right"></div>

      <span class="piece"></span>
      <span class="piece"></span>
      <span class="piece"></span>

    </div>


    <!-- Error Code -->
    <div class="error-code">
      4<span>0</span>4
    </div>


    <h1>
      Broken Link
    </h1>


    <p class="description">
      It looks like this link has broken apart.
      The page you're looking for doesn't exist
      or may have been moved.
    </p>


    <a href="/" class="home-button">
      ← Back to Home
    </a>

  </main>

</body>
</html>
```

This design gives you a more modern SaaS/website-style 404 rather than the space theme. The two chain/link pieces continuously drift apart, while the small pieces fall away to emphasize the "broken link" concept.

## Term and condition page

Below is professional, website-ready Terms & Conditions content for a web development company. You can replace the placeholders with your company name and contact details.

```
<section class="terms-and-conditions">

  <h1>Terms &amp; Conditions</h1>

  <p>
    Welcome to <strong>XYZ Web Solutions</strong>. These Terms &amp; Conditions
    govern your use of our website and the web development, design, maintenance,
    hosting, consulting, and other digital services provided by our company.
    By accessing our website or engaging our services, you agree to comply with
    these terms. If you do not agree with any part of these terms, please do not
    use our website or services.
  </p>

  <h2>1. About Our Services</h2>

  <p>
    XYZ Web Solutions provides professional website design, web development,
    e-commerce development, software development, API integration, website
    maintenance, hosting support, and related digital services. The exact scope
    of work for each project will be agreed upon with the client before the
    project begins.
  </p>

  <h3>Services may include:</h3>

  <ul>
    <li>Website design and development</li>
    <li>WordPress website development</li>
    <li>Custom PHP and web application development</li>
    <li>React and Next.js development</li>
    <li>E-commerce website development</li>
    <li>API development and third-party API integration</li>
    <li>Website maintenance and technical support</li>
    <li>Website optimization and performance improvements</li>
    <li>Domain, hosting, SSL, and deployment assistance</li>
  </ul>


  <h2>2. Project Scope</h2>

  <p>
    Each project will be developed according to the requirements, features,
    specifications, and deliverables agreed upon with the client. Any work
    outside the agreed scope may be treated as additional work and may require
    additional charges and delivery time.
  </p>


  <h2>3. Client Responsibilities</h2>

  <p>
    The client is responsible for providing accurate information, content,
    images, branding materials, credentials, approvals, and other resources
    required to complete the project.
  </p>

  <ul>
    <li>Provide required content and project information on time.</li>
    <li>Provide accurate login credentials where required.</li>
    <li>Review designs and development work within a reasonable period.</li>
    <li>Provide feedback and approvals in a timely manner.</li>
    <li>Ensure that supplied content and materials do not violate third-party rights.</li>
    <li>Maintain ownership and access to their domain and hosting accounts where applicable.</li>
  </ul>


  <h2>4. Project Changes and Revisions</h2>

  <p>
    Reasonable revisions related to the agreed project scope may be included
    depending on the project agreement. Major changes, new features, redesigns,
    additional pages, or changes to previously approved work may be considered
    additional work and may result in additional charges.
  </p>


  <h2>5. Project Timeline</h2>

  <p>
    Estimated delivery dates will be communicated based on the project scope.
    Timelines may change because of delayed content, approvals, feedback,
    third-party services, hosting issues, technical dependencies, or changes
    requested by the client.
  </p>


  <h2>6. Payments and Fees</h2>

  <p>
    Project fees, payment schedules, deposits, milestone payments, and other
    applicable charges will be agreed upon before or during the project.
    Development work may be paused if required payments are not received within
    the agreed timeframe.
  </p>

  <ul>
    <li>Payments must be made according to the agreed payment schedule.</li>
    <li>Additional features may incur additional charges.</li>
    <li>Third-party services and licenses may have separate costs.</li>
    <li>Taxes and applicable government charges may be added where applicable.</li>
  </ul>


  <h2>7. Domain and Hosting</h2>

  <p>
    Domain registration, web hosting, email hosting, SSL certificates, premium
    themes, plugins, APIs, and other third-party services may involve separate
    fees. Unless specifically agreed otherwise, the client is responsible for
    maintaining active subscriptions and renewals for third-party services.
  </p>


  <h2>8. Third-Party Services</h2>

  <p>
    Websites and applications may depend on third-party platforms, APIs,
    payment gateways, plugins, hosting providers, email services, analytics
    services, or other external providers. We are not responsible for service
    interruptions, policy changes, pricing changes, limitations, or failures
    caused by third-party providers.
  </p>


  <h2>9. Content and Intellectual Property</h2>

  <p>
    The client is responsible for ensuring that all text, images, videos,
    logos, documents, software, and other materials supplied to us are legally
    authorized for use. The client retains ownership of materials supplied by
    the client, subject to any applicable third-party rights.
  </p>

  <p>
    Ownership and licensing of the final website, source code, designs, and
    other project materials will be determined by the applicable project
    agreement and payment status.
  </p>


  <h2>10. Third-Party Copyright and Licenses</h2>

  <p>
    Some projects may use third-party libraries, fonts, plugins, themes,
    frameworks, stock images, APIs, or other licensed resources. Such resources
    remain subject to their respective licenses and terms of use.
  </p>


  <h2>11. Website Security</h2>

  <p>
    We take reasonable technical measures to develop and maintain secure
    websites. However, no website, server, software, or online service can be
    guaranteed to be completely secure. Clients are responsible for maintaining
    secure passwords, access credentials, hosting accounts, and third-party
    services.
  </p>


  <h2>12. Website Maintenance and Support</h2>

  <p>
    Maintenance and technical support are provided only when included in the
    applicable service agreement. Maintenance may include updates, bug fixes,
    backups, security checks, content changes, and other agreed services.
  </p>


  <h2>13. Warranty and Bug Fixes</h2>

  <p>
    We will make reasonable efforts to correct bugs that are directly related
    to our development work and identified within the applicable support or
    warranty period. Issues caused by unauthorized modifications, third-party
    services, hosting changes, incompatible software, or client-side changes
    may be outside the scope of warranty support.
  </p>


  <h2>14. Cancellation and Termination</h2>

  <p>
    Either party may request termination of a project subject to the applicable
    project agreement. If a project is cancelled after work has started, the
    client may be responsible for payment for work completed, approved expenses,
    third-party purchases, and other non-refundable costs incurred before
    termination.
  </p>


  <h2>15. Refund Policy</h2>

  <p>
    Refund eligibility depends on the project agreement, payment terms, work
    completed, and applicable law. Payments made for completed work,
    non-refundable third-party services, licenses, domain registrations, or
    other agreed non-refundable expenses may not be refundable.
  </p>


  <h2>16. Confidentiality</h2>

  <p>
    We respect the confidentiality of client information and will take
    reasonable measures to protect confidential project information shared
    with us. Confidential information will not be intentionally disclosed to
    unauthorized parties except where required by law or necessary to provide
    the agreed services.
  </p>


  <h2>17. Limitation of Liability</h2>

  <p>
    To the maximum extent permitted by applicable law, XYZ Web Solutions will
    not be liable for indirect, incidental, special, consequential, or business
    losses arising from the use or inability to use a website, application,
    hosting service, third-party platform, or other digital service.
  </p>


  <h2>18. Website Availability</h2>

  <p>
    We do not guarantee uninterrupted availability of websites or applications.
    Downtime may occur because of hosting failures, maintenance, network
    problems, security incidents, domain issues, third-party services, or other
    circumstances beyond our reasonable control.
  </p>


  <h2>19. Prohibited Use</h2>

  <p>
    Clients must not use websites, applications, hosting services, or software
    developed by us for unlawful activities or activities that violate
    applicable laws or third-party rights.
  </p>

  <ul>
    <li>Fraudulent or deceptive activities</li>
    <li>Distribution of malicious software</li>
    <li>Unauthorized access to systems or accounts</li>
    <li>Copyright or trademark infringement</li>
    <li>Activities that violate applicable laws or regulations</li>
  </ul>


  <h2>20. Force Majeure</h2>

  <p>
    We will not be responsible for delays or failures caused by circumstances
    beyond our reasonable control, including natural disasters, internet
    outages, infrastructure failures, government actions, cyber incidents,
    third-party service failures, or other unforeseen events.
  </p>


  <h2>21. Changes to These Terms</h2>

  <p>
    We may update these Terms &amp; Conditions from time to time to reflect
    changes to our services, business practices, legal requirements, or other
    circumstances. Updated terms will be published on this page with an
    appropriate revision date.
  </p>


  <h2>22. Governing Law</h2>

  <p>
    These Terms &amp; Conditions shall be governed by and interpreted in
    accordance with the applicable laws and jurisdiction specified in the
    applicable service agreement or, where no such agreement exists, the laws
    applicable to our business location, subject to mandatory legal
    requirements.
  </p>


  <h2>23. Contact Us</h2>

  <p>
    If you have questions about these Terms &amp; Conditions, project
    agreements, payments, or our services, please contact us using the details
    below.
  </p>

  <ul>
    <li><strong>Company:</strong> XYZ Web Solutions</li>
    <li><strong>Email:</strong> info@example.com</li>
    <li><strong>Phone:</strong> +91 XXXXX XXXXX</li>
    <li><strong>Website:</strong> www.example.com</li>
    <li><strong>Address:</strong> Your Business Address, India</li>
  </ul>


  <p>
    <strong>Last Updated:</strong> September 2026
  </p>

</section>


This is a general-purpose template, not legal advice. For a real commercial website, especially if you take online payments, host customer data, provide SaaS services, or serve international customers, it should be reviewed and adapted to your business and applicable law.

## Privacy Policy Page

Yes. For a web development company, the Privacy Policy should cover website visitors, contact-form submissions, cookies, analytics, client information, payments, third-party services, security, and user rights.

<section class="privacy-policy">

  <h1>Privacy Policy</h1>

  <p>
    At <strong>XYZ Web Solutions</strong>, we respect your privacy and are
    committed to protecting the personal information you share with us.
    This Privacy Policy explains how we collect, use, store, protect, and
    disclose information when you visit our website or use our web development,
    design, maintenance, consulting, and other digital services.
  </p>

  <p>
    By using our website or services, you acknowledge that you have read and
    understood this Privacy Policy. If you do not agree with this policy,
    please discontinue use of our website and services.
  </p>


  <h2>1. Information We Collect</h2>

  <p>
    We may collect information that you voluntarily provide to us, as well as
    certain technical information automatically collected when you use our
    website.
  </p>

  <h3>Information you provide</h3>

  <ul>
    <li>Your name and business name</li>
    <li>Email address</li>
    <li>Phone number</li>
    <li>Business address</li>
    <li>Project requirements and specifications</li>
    <li>Messages and information submitted through contact forms</li>
    <li>Information provided when requesting a quotation</li>
    <li>Account or login information where applicable</li>
    <li>Other information you voluntarily provide to us</li>
  </ul>


  <h3>Information collected automatically</h3>

  <p>
    When you visit our website, certain technical information may be collected
    automatically, depending on the technologies and services used by our
    website.
  </p>

  <ul>
    <li>IP address</li>
    <li>Browser type and version</li>
    <li>Device type</li>
    <li>Operating system</li>
    <li>Pages visited</li>
    <li>Time and date of visits</li>
    <li>Referring website or URL</li>
    <li>General website usage information</li>
    <li>Cookies and similar technologies</li>
  </ul>


  <h2>2. How We Use Your Information</h2>

  <p>
    We use collected information for legitimate business and service-related
    purposes, including:
  </p>

  <ul>
    <li>Responding to enquiries and contact requests</li>
    <li>Preparing quotations and proposals</li>
    <li>Providing web development and digital services</li>
    <li>Managing client projects</li>
    <li>Communicating about projects and services</li>
    <li>Providing customer and technical support</li>
    <li>Processing payments where applicable</li>
    <li>Maintaining and improving our website</li>
    <li>Monitoring website performance and security</li>
    <li>Preventing fraud, abuse, and unauthorized activity</li>
    <li>Complying with applicable legal obligations</li>
  </ul>


  <h2>3. Contact Forms</h2>

  <p>
    If you submit information through a contact form, quotation form, project
    enquiry, or similar form, we may collect the information you provide so
    that we can respond to your request.
  </p>

  <p>
    We may retain correspondence and enquiry information for legitimate
    business purposes, customer support, record keeping, and legal or
    administrative requirements.
  </p>


  <h2>4. Cookies</h2>

  <p>
    Our website may use cookies and similar technologies to provide essential
    functionality, remember preferences, understand website usage, and improve
    the user experience.
  </p>

  <h3>Cookies may be used for:</h3>

  <ul>
    <li>Essential website functionality</li>
    <li>Security and fraud prevention</li>
    <li>Remembering user preferences</li>
    <li>Website analytics</li>
    <li>Performance monitoring</li>
    <li>Marketing or advertising, where applicable</li>
  </ul>

  <p>
    You can control or disable cookies through your browser settings. Disabling
    certain cookies may affect some website functionality.
  </p>


  <h2>5. Analytics</h2>

  <p>
    We may use analytics services to understand how visitors use our website.
    These services may collect information such as pages visited, approximate
    location, device information, browser information, and website interaction
    data.
  </p>

  <p>
    Analytics services may use cookies or similar technologies according to
    their own privacy policies and terms.
  </p>


  <h2>6. Third-Party Services</h2>

  <p>
    We may use trusted third-party providers to operate and support our
    website and business. These providers may process certain information on
    our behalf or independently according to their own terms and privacy
    policies.
  </p>

  <ul>
    <li>Web hosting providers</li>
    <li>Domain and DNS providers</li>
    <li>Email service providers</li>
    <li>Payment processors</li>
    <li>Analytics services</li>
    <li>Cloud storage providers</li>
    <li>Security and anti-spam services</li>
    <li>Customer support tools</li>
    <li>Marketing and communication platforms</li>
    <li>Third-party APIs and software services</li>
  </ul>


  <h2>7. Payment Information</h2>

  <p>
    Where online payments are supported, payment transactions may be processed
    by third-party payment providers. We may not directly store complete
    payment-card information on our servers unless specifically stated.
  </p>

  <p>
    Payment providers may collect and process payment information according to
    their own privacy policies, security practices, and terms.
  </p>


  <h2>8. How We Protect Your Information</h2>

  <p>
    We take reasonable technical and organizational measures to protect
    personal information against unauthorized access, alteration, disclosure,
    misuse, or destruction.
  </p>

  <ul>
    <li>Access controls</li>
    <li>Secure passwords and authentication</li>
    <li>HTTPS/SSL where applicable</li>
    <li>Server and application security measures</li>
    <li>Security updates and maintenance</li>
    <li>Limited access to confidential information</li>
  </ul>

  <p>
    However, no method of transmission or electronic storage can be guaranteed
    to be completely secure.
  </p>


  <h2>9. Data Retention</h2>

  <p>
    We retain personal information only for as long as reasonably necessary
    for the purposes described in this Privacy Policy, to provide services,
    maintain business records, resolve disputes, comply with legal obligations,
    or enforce agreements.
  </p>

  <p>
    The retention period may vary depending on the type of information and the
    purpose for which it was collected.
  </p>


  <h2>10. Sharing of Personal Information</h2>

  <p>
    We do not sell personal information to third parties. We may disclose
    information where reasonably necessary to provide our services, operate
    our business, protect our rights, or comply with applicable law.
  </p>

  <ul>
    <li>Service providers working on our behalf</li>
    <li>Hosting and infrastructure providers</li>
    <li>Payment processors</li>
    <li>Professional advisers where necessary</li>
    <li>Government authorities where legally required</li>
    <li>Law enforcement where required by applicable law</li>
  </ul>


  <h2>11. Client Project Information</h2>

  <p>
    During a web development project, clients may provide information,
    documents, credentials, databases, images, source code, or other materials.
    We use such information only as reasonably necessary to perform the agreed
    services and maintain the project.
  </p>

  <p>
    Clients should avoid sending unnecessary sensitive personal information
    unless it is required for the project and appropriate safeguards have been
    discussed.
  </p>


  <h2>12. Account and Login Information</h2>

  <p>
    Where our services require an account, we may collect account information
    such as name, email address, username, authentication information, and
    related account activity.
  </p>

  <p>
    Passwords should be stored using appropriate security mechanisms and should
    never be shared with unauthorized individuals.
  </p>


  <h2>13. Email Communications</h2>

  <p>
    We may use your email address to respond to enquiries, provide project
    updates, send service-related communications, provide support, or send
    other communications relevant to our business relationship.
  </p>

  <p>
    Where applicable, promotional communications will provide an appropriate
    method for opting out of future marketing messages.
  </p>


  <h2>14. Data Breach</h2>

  <p>
    If we become aware of a security incident involving personal information,
    we will take reasonable steps to investigate, contain, and address the
    incident and provide notifications where required by applicable law.
  </p>


  <h2>15. Children's Privacy</h2>

  <p>
    Our services are intended for businesses, organizations, and general
    website users. We do not knowingly collect personal information from
    children where such collection is prohibited by applicable law.
  </p>


  <h2>16. Your Privacy Rights</h2>

  <p>
    Depending on your location and applicable law, you may have certain rights
    regarding your personal information.
  </p>

  <ul>
    <li>Request access to personal information we hold about you.</li>
    <li>Request correction of inaccurate information.</li>
    <li>Request deletion of information where legally applicable.</li>
    <li>Request restriction of certain processing.</li>
    <li>Object to certain uses of your information.</li>
    <li>Withdraw consent where processing is based on consent.</li>
    <li>Request information about how your data is processed.</li>
  </ul>

  <p>
    These rights may be subject to applicable legal limitations and
    requirements.
  </p>


  <h2>17. Third-Party Links</h2>

  <p>
    Our website may contain links to third-party websites, services, social
    media platforms, or other external resources. We are not responsible for
    the privacy practices, content, security, or policies of third-party
    websites.
  </p>

  <p>
    We recommend reviewing the privacy policy of any third-party website before
    providing personal information.
  </p>


  <h2>18. International Data Transfers</h2>

  <p>
    Some service providers we use may process or store information in countries
    other than your country of residence. Where applicable, such processing
    will be subject to appropriate contractual, technical, or legal safeguards
    required by applicable law.
  </p>


  <h2>19. Data Security Disclaimer</h2>

  <p>
    Although we take reasonable measures to protect information, no online
    system is completely secure. You acknowledge that transmission of
    information over the internet involves inherent security risks.
  </p>


  <h2>20. Changes to This Privacy Policy</h2>

  <p>
    We may update this Privacy Policy from time to time to reflect changes in
    our services, technology, business practices, or legal requirements.
    Updated versions will be published on this page with a revised
    "Last Updated" date.
  </p>


  <h2>21. Contact Us</h2>

  <p>
    If you have questions, concerns, or requests regarding this Privacy Policy
    or the handling of your personal information, please contact us.
  </p>

  <ul>
    <li>
      <strong>Company:</strong> XYZ Web Solutions
    </li>

    <li>
      <strong>Email:</strong> privacy@example.com
    </li>

    <li>
      <strong>Phone:</strong> +91 XXXXX XXXXX
    </li>

    <li>
      <strong>Website:</strong> www.example.com
    </li>

    <li>
      <strong>Address:</strong> Your Business Address, India
    </li>
  </ul>


  <p>
    <strong>Last Updated:</strong> September 2026
  </p>

</section>

Tip: If your company uses Google Analytics, Google reCAPTCHA v3, WhatsApp, Razorpay/Stripe, Mailchimp, SMTP/Nodemailer, Facebook/Meta Pixel, Google Maps, WordPress, or hosting/CDN services, those should be specifically reflected in the final Privacy Policy and cookie disclosures.

## Disclaimer Page

Certainly. For a web development company, the disclaimer should cover the website's information, development services, third-party tools, technical results, security, availability, external links, and limitation of responsibility.

<section class="disclaimer">

  <h1>Disclaimer</h1>

  <p>
    The information provided on the website of
    <strong>XYZ Web Solutions</strong> is intended for general informational
    and business purposes. While we make reasonable efforts to keep the
    information accurate and up to date, we do not guarantee that all
    information on this website is complete, accurate, current, or free from
    errors.
  </p>

  <p>
    By using this website, you acknowledge and agree to the terms of this
    Disclaimer.
  </p>


  <h2>1. General Information</h2>

  <p>
    Information published on this website may include articles, guides,
    tutorials, service descriptions, technical information, recommendations,
    examples, pricing information, and other content related to web
    development and digital services.
  </p>

  <p>
    Such information is provided for general informational purposes and should
    not be considered professional, legal, financial, cybersecurity, or other
    specialized advice.
  </p>


  <h2>2. Web Development Services</h2>

  <p>
    We provide web development, website design, WordPress development, custom
    software development, API integration, e-commerce development, website
    maintenance, hosting assistance, and related digital services.
  </p>

  <p>
    The features, functionality, performance, security, compatibility, and
    delivery time of a project depend on the agreed project requirements,
    technical environment, third-party services, hosting infrastructure, and
    other factors.
  </p>


  <h2>3. No Guarantee of Results</h2>

  <p>
    We make reasonable efforts to deliver services according to the agreed
    specifications. However, we do not guarantee specific business results,
    sales, revenue, website traffic, search-engine rankings, conversions,
    leads, advertising performance, or profitability unless expressly agreed
    in a written contract.
  </p>

  <ul>
    <li>Search engine rankings are not guaranteed.</li>
    <li>Website traffic is not guaranteed.</li>
    <li>Sales and revenue are not guaranteed.</li>
    <li>Advertising results are not guaranteed.</li>
    <li>Conversion rates are not guaranteed.</li>
    <li>Business growth is not guaranteed.</li>
  </ul>


  <h2>4. Technical Information</h2>

  <p>
    Technical information published on our website is provided for
    informational purposes. Software frameworks, programming languages,
    browsers, operating systems, APIs, hosting platforms, plugins, and other
    technologies may change over time.
  </p>

  <p>
    We do not guarantee that every example, recommendation, tutorial, or
    technical explanation will work in every environment or configuration.
  </p>


  <h2>5. Third-Party Services</h2>

  <p>
    Websites and applications may depend on third-party services such as
    hosting providers, payment gateways, APIs, plugins, themes, analytics
    platforms, email services, cloud providers, and other external systems.
  </p>

  <p>
    We are not responsible for interruptions, failures, policy changes,
    security incidents, pricing changes, limitations, or other issues caused
    by third-party services outside our reasonable control.
  </p>


  <h2>6. Website Availability</h2>

  <p>
    We make reasonable efforts to keep our website and services available.
    However, uninterrupted availability cannot be guaranteed.
  </p>

  <p>
    Website or service interruptions may occur because of maintenance,
    hosting problems, network failures, DNS issues, security incidents,
    software updates, third-party failures, or circumstances beyond our
    reasonable control.
  </p>


  <h2>7. Security Disclaimer</h2>

  <p>
    We take reasonable measures to develop and maintain secure websites and
    applications. However, no website, server, software, network, or internet
    transmission can be guaranteed to be completely secure.
  </p>

  <p>
    Clients are responsible for maintaining secure passwords, administrator
    accounts, hosting accounts, domain accounts, API credentials, and other
    access credentials under their control.
  </p>


  <h2>8. Website Performance</h2>

  <p>
    Website performance can depend on many factors, including hosting
    infrastructure, server configuration, internet connectivity, databases,
    third-party scripts, plugins, images, APIs, caching, and client-side
    devices.
  </p>

  <p>
    Therefore, specific website speed or performance results cannot be
    guaranteed unless a particular performance requirement has been expressly
    included in the applicable project agreement.
  </p>


  <h2>9. Search Engine Optimization</h2>

  <p>
    Where SEO-related services are provided, we may use generally accepted
    optimization practices. However, search engines independently determine
    their ranking systems and algorithms.
  </p>

  <p>
    We therefore do not guarantee a specific search engine ranking, position,
    traffic level, indexing result, or time required for a website to appear
    in search results.
  </p>


  <h2>10. External Links</h2>

  <p>
    Our website may contain links to third-party websites and external
    resources. These links may be provided for convenience or informational
    purposes.
  </p>

  <p>
    We do not control third-party websites and are not responsible for their
    content, availability, security, privacy practices, products, services,
    or policies.
  </p>


  <h2>11. Client-Provided Content</h2>

  <p>
    Clients are responsible for the accuracy, legality, ownership, and
    permissions associated with content, images, videos, documents, logos,
    trademarks, software, and other materials supplied to us.
  </p>

  <p>
    We are not responsible for claims arising from client-provided materials
    that infringe the intellectual property, privacy, publicity, or other
    rights of third parties.
  </p>


  <h2>12. Intellectual Property</h2>

  <p>
    Third-party software, libraries, frameworks, plugins, fonts, themes,
    stock images, icons, APIs, and other resources may be subject to separate
    licenses and terms.
  </p>

  <p>
    Use of such resources is subject to the applicable license or terms
    provided by the respective owner or provider.
  </p>


  <h2>13. Pricing Information</h2>

  <p>
    Prices, packages, offers, service descriptions, and other commercial
    information displayed on our website may change without prior notice.
    Final pricing and project scope will be determined according to the
    applicable quotation, proposal, invoice, or service agreement.
  </p>


  <h2>14. Testimonials and Portfolio</h2>

  <p>
    Testimonials, case studies, portfolio projects, and examples displayed on
    our website represent individual projects or experiences and may not
    represent results that every client will achieve.
  </p>

  <p>
    Previous project results should not be interpreted as a guarantee of
    future results.
  </p>


  <h2>15. Limitation of Liability</h2>

  <p>
    To the maximum extent permitted by applicable law, XYZ Web Solutions shall
    not be responsible for indirect, incidental, special, consequential, or
    business losses resulting from the use of information, websites,
    applications, services, third-party platforms, or external resources
    referenced on our website.
  </p>


  <h2>16. Professional Advice</h2>

  <p>
    Information on this website should not be treated as a substitute for
    professional advice. Depending on your circumstances, you should consult
    an appropriately qualified professional before making legal, financial,
    tax, cybersecurity, business, or other professional decisions.
  </p>


  <h2>17. Changes to This Disclaimer</h2>

  <p>
    We may update or modify this Disclaimer from time to time to reflect
    changes in our services, website content, business practices, or
    applicable legal requirements.
  </p>

  <p>
    Any updated version will be published on this page with a revised
    "Last Updated" date.
  </p>


  <h2>18. Contact Us</h2>

  <p>
    If you have questions about this Disclaimer or our services, please
    contact us using the information below.
  </p>

  <ul>
    <li>
      <strong>Company:</strong> XYZ Web Solutions
    </li>

    <li>
      <strong>Email:</strong> info@example.com
    </li>

    <li>
      <strong>Phone:</strong> +91 XXXXX XXXXX
    </li>

    <li>
      <strong>Website:</strong> www.example.com
    </li>

    <li>
      <strong>Address:</strong> Your Business Address, India
    </li>
  </ul>


  <p>
    <strong>Last Updated:</strong> September 2026
  </p>

</section>
```

For your company website, these four legal pages work well together:

1. Terms & Conditions — rules governing your services and client relationship.


2. Privacy Policy — how visitor/client information is collected and handled.


3. Disclaimer — limitations concerning website information, technical services, results, and third parties.


4. Cookie Policy — specifically explains cookies, analytics, tracking technologies, and cookie choices.



If you use WordPress, contact forms, Google reCAPTCHA, Google Analytics, cookies, WhatsApp, payment gateways, or email automation, I recommend adding a dedicated Cookie Policy as the fourth page.

## cookie-policy.html page

Here is a complete cookie-policy.html matching the Bootstrap-based legal pages we created. It explains essential, preference, analytics, marketing, and third-party cookies and includes cookie-management information.

```html
<!DOCTYPE html>
<html lang="en">

<head>

  <!-- =========================
       META
  ========================== -->

  <meta charset="UTF-8">

  <meta name="viewport"
        content="width=device-width, initial-scale=1">

  <meta name="description"
        content="Cookie Policy for XYZ Web Solutions explaining how cookies and similar technologies are used on our website.">

  <meta name="author"
        content="XYZ Web Solutions">

  <meta name="robots"
        content="index, follow">

  <meta name="theme-color"
        content="#0d6efd">

  <title>Cookie Policy | XYZ Web Solutions</title>


  <!-- =========================
       BOOTSTRAP 5.3
  ========================== -->

  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
    rel="stylesheet">


  <!-- =========================
       BOOTSTRAP ICONS
  ========================== -->

  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">

</head>


<body class="bg-light">


  <!-- =====================================================
       NAVBAR
  ====================================================== -->

  <nav class="navbar navbar-expand-lg bg-white border-bottom sticky-top">

    <div class="container">

      <a class="navbar-brand fw-bold fs-4"
         href="index.html">

        <i class="bi bi-code-slash text-primary"></i>

        XYZ<span class="text-primary">Web</span>

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

        <ul class="navbar-nav ms-auto align-items-lg-center gap-lg-2">

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

            <a class="nav-link"
               href="index.html#about">

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
               href="index.html#contact">

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

  <header class="bg-dark text-white py-5">

    <div class="container py-4">

      <div class="row">

        <div class="col-lg-8">

          <span class="badge text-bg-primary mb-3">

            <i class="bi bi-cookie me-1"></i>

            Legal Information

          </span>


          <h1 class="display-5 fw-bold">
            Cookie Policy
          </h1>


          <p class="lead text-white-50 mb-0">

            This policy explains how XYZ Web Solutions
            uses cookies and similar technologies on our
            website.

          </p>

        </div>

      </div>

    </div>

  </header>



  <!-- =====================================================
       CONTENT
  ====================================================== -->

  <main>

    <div class="container py-5">

      <div class="row justify-content-center">


        <div class="col-lg-9">


          <!-- Policy Introduction -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <p class="text-secondary">

                <strong>Last Updated:</strong>
                September 2026

              </p>


              <p>

                This Cookie Policy explains how
                <strong>XYZ Web Solutions</strong>
                ("we", "us", "our") uses cookies and
                similar technologies when you visit our
                website.

              </p>


              <p class="mb-0">

                Cookies help us operate our website,
                remember preferences, understand how
                visitors use our website, improve
                performance, and provide relevant
                functionality.

              </p>

            </div>

          </div>



          <!-- 1 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                1. What Are Cookies?

              </h2>


              <p>

                Cookies are small text files that may be
                placed on your computer, smartphone, tablet,
                or other device when you visit a website.

              </p>


              <p class="mb-0">

                Cookies allow a website to recognize a
                device and remember certain information
                about a user's visit or preferences.

              </p>

            </div>

          </div>



          <!-- 2 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                2. Why We Use Cookies

              </h2>


              <p>

                We may use cookies and similar technologies
                for several purposes, including:

              </p>


              <ul>

                <li>
                  Operating essential website functions.
                </li>

                <li>
                  Maintaining website security.
                </li>

                <li>
                  Remembering user preferences.
                </li>

                <li>
                  Understanding how visitors use our website.
                </li>

                <li>
                  Measuring website performance.
                </li>

                <li>
                  Improving our website and services.
                </li>

                <li>
                  Supporting marketing or advertising activities
                  where applicable.
                </li>

              </ul>

            </div>

          </div>



          <!-- 3 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                3. Types of Cookies We May Use

              </h2>


              <h3 class="h5 fw-bold mt-4">

                Essential Cookies

              </h3>

              <p>

                These cookies may be necessary for certain
                website functions, security features, navigation,
                or other essential operations.

              </p>


              <h3 class="h5 fw-bold mt-4">

                Preference Cookies

              </h3>

              <p>

                These cookies may remember choices and
                preferences made by visitors, such as language,
                region, or other settings.

              </p>


              <h3 class="h5 fw-bold mt-4">

                Analytics Cookies

              </h3>

              <p>

                These cookies may help us understand how
                visitors interact with our website, including
                which pages are visited and how users navigate
                through the website.

              </p>


              <h3 class="h5 fw-bold mt-4">

                Performance Cookies

              </h3>

              <p>

                These cookies may be used to understand
                website performance and identify technical
                issues that may affect the user experience.

              </p>


              <h3 class="h5 fw-bold mt-4">

                Marketing Cookies

              </h3>

              <p class="mb-0">

                Where applicable, marketing or advertising
                technologies may be used to understand
                interactions with advertisements or marketing
                campaigns.

              </p>

            </div>

          </div>



          <!-- 4 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                4. First-Party Cookies

              </h2>


              <p class="mb-0">

                First-party cookies are cookies placed by
                our website or by services operating directly
                on our behalf. They may be used for website
                functionality, preferences, security, analytics,
                or other purposes described in this policy.

              </p>

            </div>

          </div>



          <!-- 5 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                5. Third-Party Cookies

              </h2>


              <p>

                Some features on our website may be provided
                by third-party services. These services may
                place their own cookies or use similar tracking
                technologies.

              </p>


              <p>

                Depending on the services used by our website,
                third parties may include:

              </p>


              <ul>

                <li>Analytics providers</li>

                <li>Payment providers</li>

                <li>Social media platforms</li>

                <li>Advertising providers</li>

                <li>Security and anti-spam services</li>

                <li>Embedded media providers</li>

                <li>Customer support platforms</li>

              </ul>


              <p class="mb-0">

                Third-party providers may process information
                according to their own privacy policies and
                terms.

              </p>

            </div>

          </div>



          <!-- 6 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                6. Google Analytics

              </h2>


              <p>

                If Google Analytics or a similar analytics
                service is enabled on our website, it may use
                cookies or similar technologies to collect
                information about website usage.

              </p>


              <p class="mb-0">

                Analytics information may help us understand
                website traffic, user interactions, performance,
                and general usage patterns.

              </p>

            </div>

          </div>



          <!-- 7 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                7. Managing Cookies

              </h2>


              <p>

                Most modern web browsers allow you to view,
                block, delete, or otherwise manage cookies
                through browser settings.

              </p>


              <p>

                You can generally manage cookie settings through
                options such as:

              </p>


              <ul>

                <li>Browser privacy settings</li>

                <li>Browser security settings</li>

                <li>Cookie preferences</li>

                <li>Site permissions</li>

                <li>Browser extensions or privacy controls</li>

              </ul>


              <div class="alert alert-warning">

                <i class="bi bi-exclamation-triangle me-2"></i>

                Disabling certain cookies may affect the
                functionality or performance of parts of our
                website.

              </div>

            </div>

          </div>



          <!-- 8 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                8. Cookie Consent

              </h2>


              <p>

                Where required by applicable law, we may ask
                visitors for consent before placing certain
                non-essential cookies on their device.

              </p>


              <p class="mb-0">

                You may be able to change or withdraw your
                cookie preferences through the cookie
                preference mechanism provided on our website,
                where available.

              </p>

            </div>

          </div>



          <!-- 9 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                9. Do Not Track Signals

              </h2>


              <p class="mb-0">

                Some browsers provide "Do Not Track" or similar
                privacy settings. Because there is currently no
                universally accepted standard for responding to
                such signals, our website may not respond to all
                browser-based Do Not Track settings.

              </p>

            </div>

          </div>



          <!-- 10 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                10. Privacy Policy

              </h2>


              <p class="mb-0">

                Cookies may involve the collection or processing
                of information that is considered personal
                information under applicable laws. For additional
                information about how we collect, use, store, and
                protect personal information, please review our
                <a href="privacy-policy.html">
                  Privacy Policy
                </a>.

              </p>

            </div>

          </div>



          <!-- 11 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                11. Changes to This Cookie Policy

              </h2>


              <p class="mb-0">

                We may update this Cookie Policy from time to
                time to reflect changes in our website,
                technologies, services, legal requirements, or
                business practices.

                Updated versions will be published on this page
                with a revised "Last Updated" date.

              </p>

            </div>

          </div>



          <!-- 12 -->

          <div class="card border-0 shadow-sm mb-4">

            <div class="card-body p-4 p-md-5">

              <h2 class="h3 fw-bold mb-3">

                12. Contact Us

              </h2>


              <p>

                If you have questions about this Cookie Policy
                or how we use cookies, please contact us.

              </p>


              <ul class="list-unstyled">

                <li class="mb-2">

                  <i class="bi bi-building text-primary me-2"></i>

                  <strong>Company:</strong>
                  XYZ Web Solutions

                </li>


                <li class="mb-2">

                  <i class="bi bi-envelope text-primary me-2"></i>

                  <strong>Email:</strong>
                  privacy@example.com

                </li>


                <li class="mb-2">

                  <i class="bi bi-telephone text-primary me-2"></i>

                  <strong>Phone:</strong>
                  +91 XXXXX XXXXX

                </li>


                <li>

                  <i class="bi bi-geo-alt text-primary me-2"></i>

                  <strong>Address:</strong>
                  Your Business Address, India

                </li>

              </ul>

            </div>

          </div>



          <!-- Back Button -->

          <div class="text-center mt-5">

            <a href="index.html"
               class="btn btn-primary px-4">

              <i class="bi bi-arrow-left me-2"></i>

              Back to Home

            </a>

          </div>


        </div>

      </div>

    </div>

  </main>



  <!-- =====================================================
       FOOTER
  ====================================================== -->

  <footer class="bg-dark text-white pt-5">

    <div class="container">

      <div class="row g-4 pb-5">


        <!-- Company -->

        <div class="col-lg-4">

          <a href="index.html"
             class="text-white text-decoration-none">

            <h2 class="h4 fw-bold">

              <i class="bi bi-code-slash text-primary"></i>

              XYZ<span class="text-primary">Web</span>

            </h2>

          </a>


          <p class="text-white-50 mt-3">

            Modern websites and web applications
            built for growing businesses.

          </p>


          <div class="d-flex gap-3">

            <a href="#"
               class="text-white fs-5"
               aria-label="Facebook">

              <i class="bi bi-facebook"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="Instagram">

              <i class="bi bi-instagram"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="LinkedIn">

              <i class="bi bi-linkedin"></i>

            </a>

            <a href="#"
               class="text-white fs-5"
               aria-label="GitHub">

              <i class="bi bi-github"></i>

            </a>

          </div>

        </div>


        <!-- Quick Links -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Company
          </h3>

          <ul class="list-unstyled">

            <li class="mb-2">

              <a href="index.html#about"
                 class="text-white-50 text-decoration-none">

                About

              </a>

            </li>


            <li class="mb-2">

              <a href="index.html#services"
                 class="text-white-50 text-decoration-none">

                Services

              </a>

            </li>


            <li class="mb-2">

              <a href="index.html#portfolio"
                 class="text-white-50 text-decoration-none">

                Portfolio

              </a>

            </li>


            <li>

              <a href="index.html#contact"
                 class="text-white-50 text-decoration-none">

                Contact

              </a>

            </li>

          </ul>

        </div>


        <!-- Legal -->

        <div class="col-6 col-lg-2">

          <h3 class="h6 fw-bold">
            Legal
          </h3>

          <ul class="list-unstyled">

            <li class="mb-2">

              <a href="privacy-policy.html"
                 class="text-white-50 text-decoration-none">

                Privacy Policy

              </a>

            </li>


            <li class="mb-2">

              <a href="terms.html"
                 class="text-white-50 text-decoration-none">

                Terms &amp; Conditions

              </a>

            </li>


            <li class="mb-2">

              <a href="disclaimer.html"
                 class="text-white-50 text-decoration-none">

                Disclaimer

              </a>

            </li>


            <li>

              <a href="cookie-policy.html"
                 class="text-white-50 text-decoration-none">

                Cookie Policy

              </a>

            </li>

          </ul>

        </div>


        <!-- Contact -->

        <div class="col-lg-4">

          <h3 class="h6 fw-bold">
            Contact Us
          </h3>

          <p class="text-white-50">

            <i class="bi bi-envelope me-2"></i>

            privacy@example.com

          </p>

          <p class="text-white-50">

            <i class="bi bi-telephone me-2"></i>

            +91 XXXXX XXXXX

          </p>

          <p class="text-white-50">

            <i class="bi bi-geo-alt me-2"></i>

            Your Business Address, India

          </p>

        </div>

      </div>


      <!-- Copyright -->

      <div class="border-top border-secondary
                  py-4 text-center">

        <p class="text-white-50 mb-0">

          &copy; 2026 XYZ Web Solutions.
          All Rights Reserved.

        </p>

      </div>

    </div>

  </footer>



  <!-- =====================================================
       BOOTSTRAP JS
  ====================================================== -->

  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js">
  </script>

</body>

</html>
```

Recommended legal-page structure

Your current website can now have:

```
/
├── index.html
├── services.html
├── about.html
├── portfolio.html
├── contact.html
│
├── privacy-policy.html
├── terms.html
├── disclaimer.html
└── cookie-policy.html
```

One important implementation point: the Cookie Policy itself doesn't create cookie consent. If your site actually uses non-essential analytics/marketing cookies, you should also add a cookie-consent banner with Accept / Reject / Customize controls and ensure the relevant scripts don't load before the required consent is obtained.

## Bootstrap-based Contact Page with Netlify Compatible form

Below is a complete Bootstrap 5 contact page with a Netlify Forms-compatible form. It includes name, email, phone, service, budget, message, consent checkbox, success/error handling, and a responsive layout.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Contact XYZ Web Solutions for website development, WordPress, e-commerce, web applications and API development.">

    <meta name="author" content="XYZ Web Solutions">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#212529">

    <title>Contact Us | XYZ Web Solutions</title>

    <!-- Bootstrap 5 -->
    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
        rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    <style>
        body {
            background-color: #f8f9fa;
            color: #212529;
        }

        .navbar-brand {
            font-weight: 700;
        }

        .page-header {
            background: linear-gradient(135deg, #212529, #343a40);
            color: #fff;
            padding: 90px 0;
        }

        .page-header h1 {
            font-weight: 700;
        }

        .contact-card {
            border: 0;
            border-radius: 15px;
            box-shadow: 0 8px 30px rgba(0, 0, 0, 0.08);
        }

        .contact-info {
            height: 100%;
            background: #212529;
            color: #fff;
            border-radius: 15px;
            padding: 35px;
        }

        .contact-info-item {
            display: flex;
            gap: 15px;
            margin-bottom: 25px;
        }

        .contact-info-item i {
            font-size: 1.4rem;
            color: #0d6efd;
        }

        .contact-info-item h6 {
            margin-bottom: 5px;
        }

        .contact-info-item p {
            margin: 0;
            color: #ced4da;
        }

        .contact-info a {
            color: #ced4da;
            text-decoration: none;
        }

        .contact-info a:hover {
            color: #fff;
        }

        .form-control,
        .form-select {
            padding: 12px 15px;
            border-radius: 8px;
        }

        .form-control:focus,
        .form-select:focus {
            box-shadow: 0 0 0 0.2rem rgba(13, 110, 253, 0.15);
        }

        .btn-submit {
            padding: 12px 28px;
            border-radius: 8px;
            font-weight: 600;
        }

        .required {
            color: #dc3545;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
            background: #343a40;
            color: #fff;
            text-decoration: none;
            margin-right: 8px;
            transition: 0.3s;
        }

        .social-links a:hover {
            background: #0d6efd;
            transform: translateY(-2px);
        }

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
    </style>
</head>

<body>

<!-- =========================
     NAVBAR
========================= -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">

        <a class="navbar-brand" href="index.html">
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

        <div class="collapse navbar-collapse" id="mainNavbar">

            <ul class="navbar-nav ms-auto">

                <li class="nav-item">
                    <a class="nav-link" href="index.html">
                        Home
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html#services">
                        Services
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="index.html#about">
                        About
                    </a>
                </li>

                <li class="nav-item">
                    <a class="nav-link active" href="contact.html">
                        Contact
                    </a>
                </li>

            </ul>

        </div>
    </div>
</nav>


<!-- =========================
     PAGE HEADER
========================= -->
<header class="page-header text-center">

    <div class="container">

        <span class="badge bg-primary mb-3 px-3 py-2">
            <i class="bi bi-envelope me-1"></i>
            Get In Touch
        </span>

        <h1>Contact Us</h1>

        <p class="lead mb-0">
            Have a project in mind? Let's discuss how we can help your business grow.
        </p>

    </div>

</header>


<!-- =========================
     CONTACT SECTION
========================= -->
<section class="py-5">

    <div class="container">

        <div class="row g-4 align-items-stretch">

            <!-- =========================
                 CONTACT INFORMATION
            ========================== -->
            <div class="col-lg-5">

                <div class="contact-info">

                    <h2 class="mb-3">
                        Let's Talk
                    </h2>

                    <p class="mb-4">
                        Tell us about your project, requirements or business idea.
                        We'll get back to you as soon as possible.
                    </p>


                    <!-- Email -->
                    <div class="contact-info-item">

                        <i class="bi bi-envelope"></i>

                        <div>
                            <h6>Email</h6>

                            <p>
                                <a href="mailto:info@example.com">
                                    info@example.com
                                </a>
                            </p>
                        </div>

                    </div>


                    <!-- Phone -->
                    <div class="contact-info-item">

                        <i class="bi bi-telephone"></i>

                        <div>
                            <h6>Phone</h6>

                            <p>
                                <a href="tel:+91XXXXXXXXXX">
                                    +91 XXXXX XXXXX
                                </a>
                            </p>
                        </div>

                    </div>


                    <!-- Location -->
                    <div class="contact-info-item">

                        <i class="bi bi-geo-alt"></i>

                        <div>
                            <h6>Location</h6>

                            <p>
                                Your Business Address<br>
                                Gujarat, India
                            </p>
                        </div>

                    </div>


                    <!-- Business Hours -->
                    <div class="contact-info-item">

                        <i class="bi bi-clock"></i>

                        <div>
                            <h6>Business Hours</h6>

                            <p>
                                Monday – Saturday<br>
                                10:00 AM – 7:00 PM
                            </p>
                        </div>

                    </div>


                    <!-- Social Links -->
                    <div class="social-links mt-4">

                        <a href="#" aria-label="Facebook">
                            <i class="bi bi-facebook"></i>
                        </a>

                        <a href="#" aria-label="Instagram">
                            <i class="bi bi-instagram"></i>
                        </a>

                        <a href="#" aria-label="LinkedIn">
                            <i class="bi bi-linkedin"></i>
                        </a>

                        <a href="#" aria-label="GitHub">
                            <i class="bi bi-github"></i>
                        </a>

                    </div>

                </div>

            </div>


            <!-- =========================
                 NETLIFY FORM
            ========================== -->
            <div class="col-lg-7">

                <div class="card contact-card h-100">

                    <div class="card-body p-4 p-lg-5">

                        <h2 class="mb-2">
                            Send Us a Message
                        </h2>

                        <p class="text-muted mb-4">
                            Fill out the form below and we'll contact you shortly.
                        </p>


                        <!--
                            NETLIFY FORM

                            Important:
                            - data-netlify="true"
                            - name="contact"
                            - hidden form-name input
                            - Each input needs a name attribute
                        -->

                        <form
                            name="contact"
                            method="POST"
                            action="/contact-success.html"
                            data-netlify="true"
                            netlify-honeypot="bot-field">

                            <!-- Netlify Form Identification -->
                            <input
                                type="hidden"
                                name="form-name"
                                value="contact">


                            <!-- Honeypot Spam Protection -->
                            <p class="d-none">

                                <label>
                                    Don't fill this out if you're human:

                                    <input
                                        name="bot-field">
                                </label>

                            </p>


                            <div class="row g-3">

                                <!-- Name -->
                                <div class="col-md-6">

                                    <label
                                        for="name"
                                        class="form-label">

                                        Full Name
                                        <span class="required">*</span>

                                    </label>

                                    <input
                                        type="text"
                                        class="form-control"
                                        id="name"
                                        name="name"
                                        placeholder="Enter your name"
                                        autocomplete="name"
                                        required>

                                </div>


                                <!-- Email -->
                                <div class="col-md-6">

                                    <label
                                        for="email"
                                        class="form-label">

                                        Email Address
                                        <span class="required">*</span>

                                    </label>

                                    <input
                                        type="email"
                                        class="form-control"
                                        id="email"
                                        name="email"
                                        placeholder="you@example.com"
                                        autocomplete="email"
                                        required>

                                </div>


                                <!-- Phone -->
                                <div class="col-md-6">

                                    <label
                                        for="phone"
                                        class="form-label">

                                        Phone Number

                                    </label>

                                    <input
                                        type="tel"
                                        class="form-control"
                                        id="phone"
                                        name="phone"
                                        placeholder="+91 XXXXX XXXXX"
                                        autocomplete="tel">

                                </div>


                                <!-- Company -->
                                <div class="col-md-6">

                                    <label
                                        for="company"
                                        class="form-label">

                                        Company

                                    </label>

                                    <input
                                        type="text"
                                        class="form-control"
                                        id="company"
                                        name="company"
                                        placeholder="Company name"
                                        autocomplete="organization">

                                </div>


                                <!-- Service -->
                                <div class="col-md-6">

                                    <label
                                        for="service"
                                        class="form-label">

                                        Service
                                        <span class="required">*</span>

                                    </label>

                                    <select
                                        class="form-select"
                                        id="service"
                                        name="service"
                                        required>

                                        <option value="">
                                            Select a service
                                        </option>

                                        <option value="Website Development">
                                            Website Development
                                        </option>

                                        <option value="WordPress Development">
                                            WordPress Development
                                        </option>

                                        <option value="E-Commerce Development">
                                            E-Commerce Development
                                        </option>

                                        <option value="Custom Web Application">
                                            Custom Web Application
                                        </option>

                                        <option value="API Development">
                                            API Development
                                        </option>

                                        <option value="Website Maintenance">
                                            Website Maintenance
                                        </option>

                                        <option value="Other">
                                            Other
                                        </option>

                                    </select>

                                </div>


                                <!-- Budget -->
                                <div class="col-md-6">

                                    <label
                                        for="budget"
                                        class="form-label">

                                        Estimated Budget

                                    </label>

                                    <select
                                        class="form-select"
                                        id="budget"
                                        name="budget">

                                        <option value="">
                                            Select budget
                                        </option>

                                        <option value="Under ₹25,000">
                                            Under ₹25,000
                                        </option>

                                        <option value="₹25,000 - ₹50,000">
                                            ₹25,000 - ₹50,000
                                        </option>

                                        <option value="₹50,000 - ₹1,00,000">
                                            ₹50,000 - ₹1,00,000
                                        </option>

                                        <option value="₹1,00,000+">
                                            ₹1,00,000+
                                        </option>

                                        <option value="Not sure">
                                            Not sure
                                        </option>

                                    </select>

                                </div>


                                <!-- Subject -->
                                <div class="col-12">

                                    <label
                                        for="subject"
                                        class="form-label">

                                        Subject
                                        <span class="required">*</span>

                                    </label>

                                    <input
                                        type="text"
                                        class="form-control"
                                        id="subject"
                                        name="subject"
                                        placeholder="How can we help?"
                                        required>

                                </div>


                                <!-- Message -->
                                <div class="col-12">

                                    <label
                                        for="message"
                                        class="form-label">

                                        Message
                                        <span class="required">*</span>

                                    </label>

                                    <textarea
                                        class="form-control"
                                        id="message"
                                        name="message"
                                        rows="6"
                                        placeholder="Tell us about your project..."
                                        required></textarea>

                                </div>


                                <!-- Consent -->
                                <div class="col-12">

                                    <div class="form-check">

                                        <input
                                            class="form-check-input"
                                            type="checkbox"
                                            id="consent"
                                            name="consent"
                                            value="Yes"
                                            required>

                                        <label
                                            class="form-check-label"
                                            for="consent">

                                            I agree to the
                                            <a href="privacy-policy.html">
                                                Privacy Policy
                                            </a>
                                            and understand that my information
                                            will be used to respond to my inquiry.

                                        </label>

                                    </div>

                                </div>


                                <!-- Submit -->
                                <div class="col-12">

                                    <button
                                        type="submit"
                                        class="btn btn-primary btn-submit">

                                        <i class="bi bi-send me-2"></i>
                                        Send Message

                                    </button>

                                </div>

                            </div>

                        </form>

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     FAQ / CTA
========================= -->
<section class="py-5 bg-white">

    <div class="container">

        <div class="text-center">

            <h2>
                Have a Quick Question?
            </h2>

            <p class="text-muted">
                You can also email us directly.
            </p>

            <a
                href="mailto:info@example.com"
                class="btn btn-outline-primary">

                <i class="bi bi-envelope me-2"></i>
                Email Us

            </a>

        </div>

    </div>

</section>


<!-- =========================
     FOOTER
========================= -->
<footer class="py-5">

    <div class="container">

        <div class="row g-4">

            <!-- Company -->
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


            <!-- Quick Links -->
            <div class="col-md-6 col-lg-4">

                <h5 class="text-white">
                    Quick Links
                </h5>

                <ul class="list-unstyled">

                    <li class="mb-2">
                        <a href="index.html">Home</a>
                    </li>

                    <li class="mb-2">
                        <a href="index.html#services">Services</a>
                    </li>

                    <li class="mb-2">
                        <a href="index.html#about">About</a>
                    </li>

                    <li class="mb-2">
                        <a href="contact.html">Contact</a>
                    </li>

                </ul>

            </div>


            <!-- Legal -->
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


<!-- Bootstrap JS -->
<script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js">
</script>

</body>
</html>
```

Add a Netlify success page

Because the form uses:

action="/contact-success.html"

create this file in the same directory:


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0">

    <title>Message Sent | XYZ Web Solutions</title>

    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
        rel="stylesheet">

    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>

<body class="bg-light">

    <div
        class="container min-vh-100 d-flex align-items-center justify-content-center">

        <div class="card shadow-sm border-0 text-center"
             style="max-width: 600px;">

            <div class="card-body p-5">

                <div class="mb-4">

                    <i
                        class="bi bi-check-circle-fill text-success"
                        style="font-size: 4rem;">
                    </i>

                </div>

                <h1 class="mb-3">
                    Message Sent Successfully!
                </h1>

                <p class="text-muted mb-4">
                    Thank you for contacting XYZ Web Solutions.
                    We have received your message and will get back
                    to you shortly.
                </p>

                <a
                    href="index.html"
                    class="btn btn-primary me-2">

                    <i class="bi bi-house me-2"></i>
                    Back to Home

                </a>

                <a
                    href="contact.html"
                    class="btn btn-outline-secondary">

                    Send Another Message

                </a>

            </div>

        </div>

    </div>

</body>
</html>
```

Netlify setup

The important part is this form declaration:

```
<form
    name="contact"
    method="POST"
    action="/contact-success.html"
    data-netlify="true"
    netlify-honeypot="bot-field">
```

When you deploy the site to Netlify, Netlify detects the form and collects submissions under:

Netlify Dashboard → Your Site → Forms → contact

You can also configure email notifications from the Netlify dashboard so that new contact-form submissions are forwarded to your business email.

Your resulting structure can be:

```
website/
│
├── index.html
├── services.html
├── about.html
├── portfolio.html
├── contact.html
├── contact-success.html
│
├── privacy-policy.html
├── terms.html
├── disclaimer.html
├── cookie-policy.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── images/
```

One important point: Netlify Forms only works after the site is deployed to Netlify; opening contact.html directly from your computer with file:// will not process submissions.

## Bootstrap contact-success page

Here is a polished, responsive contact-success.html that matches the XYZ Web Solutions Bootstrap website and includes a success message, contact details, and navigation back to the website.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Thank you for contacting XYZ Web Solutions. Your message has been received successfully.">

    <meta name="author"
          content="XYZ Web Solutions">

    <meta name="robots"
          content="noindex, nofollow">

    <meta name="theme-color"
          content="#212529">

    <title>Message Sent Successfully | XYZ Web Solutions</title>

    <!-- Bootstrap 5 -->
    <link
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css"
        rel="stylesheet">

    <!-- Bootstrap Icons -->
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    <style>

        body {
            min-height: 100vh;
            background:
                linear-gradient(
                    135deg,
                    #f8f9fa 0%,
                    #e9ecef 100%
                );

            color: #212529;
        }

        .success-wrapper {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 30px 15px;
        }

        .success-card {
            width: 100%;
            max-width: 650px;
            background: #fff;
            border: 0;
            border-radius: 20px;
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.10);
            overflow: hidden;
        }

        .success-header {
            background: linear-gradient(
                135deg,
                #212529,
                #343a40
            );

            padding: 45px 30px;
            text-align: center;
            color: #fff;
        }

        .success-icon {
            width: 90px;
            height: 90px;

            display: inline-flex;
            align-items: center;
            justify-content: center;

            background: #198754;
            color: #fff;

            border-radius: 50%;

            font-size: 45px;

            margin-bottom: 20px;

            animation: successPop 0.6s ease;
        }

        @keyframes successPop {

            0% {
                transform: scale(0);
                opacity: 0;
            }

            70% {
                transform: scale(1.1);
            }

            100% {
                transform: scale(1);
                opacity: 1;
            }

        }

        .success-body {
            padding: 45px 35px;
            text-align: center;
        }

        .success-body h1 {
            font-weight: 700;
            margin-bottom: 15px;
        }

        .success-body p {
            color: #6c757d;
            line-height: 1.7;
        }

        .next-steps {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 20px;
            margin: 30px 0;
            text-align: left;
        }

        .next-step {
            display: flex;
            align-items: flex-start;
            gap: 12px;
            margin-bottom: 15px;
        }

        .next-step:last-child {
            margin-bottom: 0;
        }

        .next-step i {
            color: #198754;
            font-size: 1.2rem;
            margin-top: 2px;
        }

        .next-step span {
            color: #495057;
        }

        .btn-home {
            padding: 12px 25px;
            border-radius: 8px;
            font-weight: 600;
        }

        .btn-contact {
            padding: 12px 25px;
            border-radius: 8px;
            font-weight: 600;
        }

        .contact-info {
            margin-top: 30px;
            padding-top: 25px;
            border-top: 1px solid #dee2e6;
        }

        .contact-info a {
            color: #0d6efd;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .footer-text {
            font-size: 0.85rem;
            color: #6c757d;
            margin-top: 25px;
            margin-bottom: 0;
        }

    </style>
</head>

<body>

    <main class="success-wrapper">

        <div class="success-card">

            <!-- =========================
                 HEADER
            ========================== -->
            <div class="success-header">

                <div class="success-icon">

                    <i class="bi bi-check-lg"></i>

                </div>

                <h2 class="mb-0">
                    Thank You!
                </h2>

            </div>


            <!-- =========================
                 BODY
            ========================== -->
            <div class="success-body">

                <h1>
                    Message Sent Successfully
                </h1>

                <p class="lead">
                    We've received your message and appreciate
                    you taking the time to contact us.
                </p>

                <p>
                    Our team will review your inquiry and get back
                    to you as soon as possible.
                </p>


                <!-- =========================
                     NEXT STEPS
                ========================== -->
                <div class="next-steps">

                    <div class="next-step">

                        <i class="bi bi-check-circle-fill"></i>

                        <span>
                            Your contact form has been successfully submitted.
                        </span>

                    </div>

                    <div class="next-step">

                        <i class="bi bi-envelope-check-fill"></i>

                        <span>
                            Our team will review your requirements.
                        </span>

                    </div>

                    <div class="next-step">

                        <i class="bi bi-chat-dots-fill"></i>

                        <span>
                            We'll contact you using the details you provided.
                        </span>

                    </div>

                </div>


                <!-- =========================
                     BUTTONS
                ========================== -->

                <div class="d-flex flex-column flex-sm-row
                            justify-content-center gap-2">

                    <a
                        href="index.html"
                        class="btn btn-primary btn-home">

                        <i class="bi bi-house-door me-2"></i>
                        Back to Home

                    </a>

                    <a
                        href="contact.html"
                        class="btn btn-outline-secondary btn-contact">

                        <i class="bi bi-envelope me-2"></i>
                        Send Another Message

                    </a>

                </div>


                <!-- =========================
                     CONTACT INFO
                ========================== -->

                <div class="contact-info">

                    <p class="mb-2">
                        Need to contact us directly?
                    </p>

                    <a href="mailto:info@example.com">

                        <i class="bi bi-envelope me-1"></i>
                        info@example.com

                    </a>

                    <span class="mx-2 text-muted">
                        |
                    </span>

                    <a href="tel:+91XXXXXXXXXX">

                        <i class="bi bi-telephone me-1"></i>
                        +91 XXXXX XXXXX

                    </a>

                </div>


                <!-- =========================
                     COPYRIGHT
                ========================== -->

                <p class="footer-text">
                    &copy; 2026 XYZ Web Solutions.
                    All Rights Reserved.
                </p>

            </div>

        </div>

    </main>


    <!-- Bootstrap JS -->
    <script
        src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js">
    </script>

</body>

</html>
```

Your Netlify form should point to it exactly as:

action="/contact-success.html"

So the flow becomes:

Contact Form → Netlify receives submission → contact-success.html → User sees success page.

## robot.txt for Disallow term

For your website, create a file named robots.txt in the root directory:

```text
User-agent: *
Allow: /
Disallow: /404-1.html
Disallow: /404-2.html

sitemap: https://XYZ.com/sitemap.xml
```

This tells search-engine crawlers not to crawl those two pages.

Your structure would be:

```
/
├── index.html
├── contact.html
├── contact-success.html
├── 404-1.html
├── 404-2.html
├── robots.txt
├── privacy-policy.html
├── terms.html
├── disclaimer.html
└── cookie-policy.html
```

If these are your custom 404 error pages, I would also recommend configuring your hosting/Netlify settings so that the appropriate 404 page is actually served for missing URLs.

## Meta tag for no index pages

To prevent a page from being indexed by search engines, add this inside the <head>:

```
<meta name="robots" content="noindex, nofollow">
```

Recommended for your 404 pages

For 404-1.html and 404-2.html:

```
<head>
    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta name="robots" content="noindex, nofollow">

    <title>Page Not Found | XYZ Web Solutions</title>
</head>
```

Other useful variations

No indexing, but allow links to be followed:

```
<meta name="robots" content="noindex, follow">
```

Prevent indexing and prevent cached copies:
```
<meta name="robots" content="noindex, nofollow, noarchive">
```

For a 404 page, I recommend:

```
<meta name="robots" content="noindex, nofollow">
```

Also, the noindex meta tag is generally more appropriate than relying on robots.txt to keep a page out of search results.