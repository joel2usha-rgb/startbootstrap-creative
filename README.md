doctype html
html(lang='en')

    head

        meta(charset='utf-8')
        meta(name='viewport', content='width=device-width, initial-scale=1, shrink-to-fit=no')
        meta(name='description', content='')
        meta(name='author', content='')

        title Creative - Start Bootstrap Theme

        // Favicon
        link(rel='icon', type='image/x-icon', href='assets/img/favicon.ico')

        // Font Awesome icons (free version)
        script(src='https://use.fontawesome.com/releases/v5.13.0/js/all.js', crossorigin='anonymous')

        // Google fonts
        link(href='https://fonts.googleapis.com/css?family=Merriweather+Sans:400,700', rel='stylesheet')
        link(href='https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic', rel='stylesheet', type='text/css')

        // Third party plugin CSS
        link(href='https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.min.css', rel='stylesheet')

        // Core theme CSS (includes Bootstrap)
        link(href='css/styles.css', rel='stylesheet')

    body#page-top

        // Navigation
        nav#mainNav.navbar.navbar-expand-lg.navbar-light.fixed-top.py-3
            .container
                a.navbar-brand.js-scroll-trigger(href='#page-top') Korea Family Market
                button.navbar-toggler.navbar-toggler-right(type='button', data-toggle='collapse', data-target='#navbarResponsive', aria-controls='navbarResponsive', aria-expanded='false', aria-label='Toggle navigation')
                    span.navbar-toggler-icon
                #navbarResponsive.collapse.navbar-collapse
                    ul.navbar-nav.ml-auto.my-2.my-lg-0
                        li.nav-item
                            a.nav-link.js-scroll-trigger(href='#about') About
                        li.nav-item
                            a.nav-link.js-scroll-trigger(href='#services') Services
                        li.nav-item
                            a.nav-link.js-scroll-trigger(href='#portfolio') Portfolio
                        li.nav-item
                            a.nav-link.js-scroll-trigger(href='#contact') Contact

        // Masthead
        header.masthead
            .container.h-100
                .row.h-100.align-items-center.justify-content-center.text-center
                    .col-lg-10.align-self-end
                        h1.text-uppercase.text-white.font-weight-bold Welcome to Korea Family Market
                        hr.divider.my-4
                    .col-lg-8.align-self-baseline
                        p.text-white-75.font-weight-light.mb-5
                            |Korea Family Market is a a market place where businesses grow and flourish|
                        a.btn.btn-primary.btn-xl.js-scroll-trigger(href='#about') Find Out More

        // About
        section#about.page-section.bg-primary
            .container
                .row.justify-content-center
                    .col-lg-8.text-center
                        h2.text-white.mt-0 We've got what you need!
                        hr.divider.light.my-4
                        p.text-white-50.mb-4
                            
                        a.btn.btn-light.btn-xl.js-scroll-trigger(href='#services') Get Started!

        // Services
        section#services.page-section
            .container
                h2.text-center.mt-0 At Your Service
                hr.divider.my-4
                .row
                    .col-lg-3.col-md-6.text-center
                        .mt-5
                            i.fas.fa-4x.fa-gem.text-primary.mb-4
                            h3.h4.mb-2 Sturdy Themes
                            p.text-muted.mb-0 Our themes are updated regularly to keep them bug free!
                    .col-lg-3.col-md-6.text-center
                        .mt-5
                            i.fas.fa-4x.fa-laptop-code.text-primary.mb-4
                            h3.h4.mb-2 Up to Date
                            p.text-muted.mb-0 All dependencies are kept current to keep things fresh.
                    .col-lg-3.col-md-6.text-center
                        .mt-5
                            i.fas.fa-4x.fa-globe.text-primary.mb-4
                            h3.h4.mb-2 Ready to Publish
                            p.text-muted.mb-0 You can use this design as is, or you can make changes!
                    .col-lg-3.col-md-6.text-center
                        .mt-5
                            i.fas.fa-4x.fa-heart.text-primary.mb-4
                            h3.h4.mb-2 Made with Love
                            p.text-muted.mb-0 Is it really open source if it's not made with love?

        // Portfolio
        div#portfolio
            .container-fluid.p-0
                .row.no-gutters
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/1.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/1.jpg', alt='')
                            .portfolio-box-caption
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/2.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/2.jpg', alt='')
                            .portfolio-box-caption
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/3.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/3.jpg', alt='')
                            .portfolio-box-caption
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/4.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/4.jpg', alt='')
                            .portfolio-box-caption
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/5.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/5.jpg', alt='')
                            .portfolio-box-caption
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name
                    .col-lg-4.col-sm-6
                        a.portfolio-box(href='assets/img/portfolio/fullsize/6.jpg')
                            img.img-fluid(src='assets/img/portfolio/thumbnails/6.jpg', alt='')
                            .portfolio-box-caption.p-3
                                .project-category.text-white-50
                                    | Category
                                .project-name
                                    | Project Name

        // Call to action
        section.page-section.bg-dark.text-white
            .container.text-center
                h2.mb-4 Free Download at Start Bootstrap!
                a.btn.btn-light.btn-xl(href='https://startbootstrap.com/themes/creative/') Download Now!

        // Contact
        section#contact.page-section
            .container
                .row.justify-content-center
                    .col-lg-8.text-center
                        h2.mt-0 Let's Get In Touch!
                        hr.divider.my-4
                        p.text-muted.mb-5
                            | Ready to shop  with us? Give us a call or send us an email and we will get back to you as soon as possible!
                .row
                    .col-lg-4.ml-auto.text-center.mb-5.mb-lg-0
                        i.fas.fa-phone.fa-3x.mb-3.text-muted
                        div +1 (555) 123-4567
                    .col-lg-4.mr-auto.text-center
                        i.fas.fa-envelope.fa-3x.mb-3.text-muted

                        // Make sure to change the email address in BOTH the anchor text and the link target below!
                        a.d-block(href='mailto:contact@yourwebsite.com') contact@yourwebsite.com

        // Footer
        footer.bg-light.py-5
            .container
                .small.text-center.text-muted Copyright © 2020 - Korea Family Market

        // Bootstrap core JS
        script(src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js')
        script(src='https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.bundle.min.js')

        // Third party plugin JS
        script(src='https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js')
        script(src='https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js')

        // Core theme JS
        script(src='js/scripts.js')
Copyright 2013-2020 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-creative/blob/gh-pages/LICENSE) license.
