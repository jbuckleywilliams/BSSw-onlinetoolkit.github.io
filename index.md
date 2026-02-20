<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0" />
    <meta name="csrf-token" content="IYlLTKflz3rz8oKFKQRObuDaVKC5DsHzGpZKLrRU" />
    <!-- Fav / CSS -->
    <link href="https://perstarke-webdev.de/assets_frontend/assets/images/fav.webp" type="image/x-icon" rel="shortcut icon" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/css/bootstrap.min.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/css/slick.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/fonts/boxicons/boxicons.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/css/slick-theme.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/css/style.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/assets_frontend/assets/css/responsive.css" rel="stylesheet" />
    <link href="https://perstarke-webdev.de/plugins/toastr/toastr.min.css" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/toastr.js/latest/toastr.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>
      PSWD
    </title>
    <style>
    </style>
    <link rel="canonical" href="https://perstarke-webdev.de/oneflow-jekyll-theme" />
    <!-- GA4 -->
    <script async="" src="https://www.googletagmanager.com/gtag/js?id=G-VKBG5ESDVE">
    </script>
    <script>
      window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag(&#39;js&#39;, new Date());
        gtag(&#39;config&#39;, &#39;G-VKBG5ESDVE&#39;);
    </script>
  </head>
  <body>
    <!-- responsive header Start here -->
    <style>
      .language-switcher a {
        text-decoration: none;
        margin: 0 5px;
        color: #333;
    }
    .language-switcher a.active {
        font-weight: bold;
        text-decoration: underline;
    }
    </style>
    <div class="responsive_header">
      <div class="crs_btn">
        <i class="bx bx-x"></i>
      </div>
      <ul class="responsive_nav">
        <li>
          <a href="https://perstarke-webdev.de/project">          Projects
</a>
        </li>
        <li>
          <a href="https://perstarke-webdev.de/services">          Services
</a>
        </li>
        <li>
          <a href="https://perstarke-webdev.de/about-us">          About
</a>
        </li>
        <li>
          <a href="https://perstarke-webdev.de/blog">          Blog
</a>
        </li>
      </ul>
      <div class="header_btn">
        <a href="https://perstarke-webdev.de/contact-us" class="themebtn pop_btn">        Let&#39;s Talk
</a>
      </div>
    </div>
    <!-- responsive header end here -->
    <!-- header start here -->
    <header class="header">
      <div class="container">
        <div class="main_header">
          <a href="https://perstarke-webdev.de" class="logo">          <img src="https://perstarke-webdev.de/uploads/logos/1753176004_logo.webp" alt="Logo" class="img__contain" width="800" height="600" />
</a>
          <div class="header_right">
            <!-- header nav start -->
            <ul class="header_nav">
              <li>
                <a href="https://perstarke-webdev.de/project">                Projects
</a>
              </li>
              <li>
                <a href="https://perstarke-webdev.de/services">                Services
</a>
              </li>
              <li>
                <a href="https://perstarke-webdev.de/about-us">                About
</a>
              </li>
              <li>
                <a href="https://perstarke-webdev.de/blog">                Blog
</a>
              </li>
            </ul>
            <!-- header nav end-->
            <div class="header_btn">
              <a href="https://perstarke-webdev.de/contact-us" class="themebtn pop_btn">              Let&#39;s Talk
</a>
            </div>
            <!-- Trigger Button -->
            <button id="openSearch" class="search-trigger" aria-label="Open search">
              <i class="fas fa-search"></i>
            </button>
            <div style="display: flex;" class="language-switcher">
              <a href="https://perstarke-webdev.de/lang/de" class="">              <img src="https://perstarke-webdev.de/assets_frontend/assets/germany.svg" alt="German" width="20" />
</a>
              |
              <a href="https://perstarke-webdev.de/lang/en" class="active">              <img src="https://perstarke-webdev.de/assets_frontend/assets/US.png" alt="English" width="20" />
</a>
            </div>
          </div>
          <div class="MobileSearch d-flex">
            <div style="display: flex;" class="language-switcher">
              <a href="https://perstarke-webdev.de/lang/de" class="">              <img src="https://perstarke-webdev.de/assets_frontend/assets/germany.svg" alt="German" width="20" />
</a>
              |
              <a href="https://perstarke-webdev.de/lang/en" class="active">              <img src="https://perstarke-webdev.de/assets_frontend/assets/US.png" alt="English" width="20" />
</a>
            </div>
            <button id="openSearch" class="search-trigger" aria-label="Open search">
              <i class="fas fa-search" aria-hidden="true"></i>
            </button>
            <div class="menu_btn">
              <span></span>
              <span></span>
              <span></span>
            </div>
          </div>
        </div>
        <!-- Search Icon Trigger -->
        <!-- Font Awesome -->
        <!-- Fullscreen Search Modal -->
        <div id="searchModal" class="search-modal">
          <div class="search-modal-overlay">
            <div class="search-modal-content">
              <form action="https://perstarke-webdev.de/search" method="GET" class="search-form">
                <input type="text" name="query" placeholder="Type to search..." required="" />
                <button type="submit">
                  <i class="fas fa-search"></i>
                </button>
              </form>
              <span id="closeSearch" class="close-search">              ×
</span>
            </div>
          </div>
        </div>
        <style>
          /* Trigger button */
            .search-trigger {
                background: none;
                border: none;
                font-size: 22px;
                cursor: pointer;
            }

            /* Modal Overlay */
            .search-modal {
                display: none;
                position: fixed;
                z-index: 9999;
                top: 0;
                left: 0;
                width: 100%;
                height: 100%;
                background: rgba(0,0,0,0.9);
                justify-content: center;
                align-items: center;
                animation: fadeIn 0.3s ease-in-out;
            }

            .search-modal-overlay {
                width: 100%;
                height: 100%;
                display: flex;
                justify-content: center;
                align-items: center;
                max-width: 100%;
            }
    .search-modal-content{
        width: 50%;
    }
    @media screen and (max-width:991px){
        .search-modal-content{
            width: 100%;
        }
    }
            @media screen and (min-width:850px){
                .MobileSearch{
                    display: none !important;
                }
            }
            .MobileSearch{
                gap: 20px;
            }

            /* Search Form */
            .search-form {
                display: flex;
            }

            .search-form input {
                flex: 1;
                padding: 15px;
                font-size: 18px;
                border-radius: 50px 0 0 50px;
                border: 1px solid #ccc;
                outline: none;
                width: 100%;
            }

            .search-form button {
                padding: 15px 25px;
                font-size: 18px;
                border-radius: 0 50px 50px 0;
                border: none;
                background: #4a64f6;
                color: white;
                cursor: pointer;
            }

            /* Close button */
            .close-search {
                position: absolute;
                top: 10px;
                right: 25px;
                font-size: 38px;
                color: #fff;
                cursor: pointer;
            }

            /* Animations */
            @keyframes fadeIn {
                from { opacity: 0; }
                to { opacity: 1; }
            }

            @keyframes slideDown {
                from { transform: translateY(-50px); opacity: 0; }
                to { transform: translateY(0); opacity: 1; }
            }
        </style>
        <script>
          document.addEventListener(&#39;DOMContentLoaded&#39;, function () {
                const openButtons = document.querySelectorAll(&#39;[id=&#34;openSearch&#34;]&#39;); // all elements with id=&#34;openSearch&#34;
                const closeBtn = document.getElementById(&#39;closeSearch&#39;);
                const modal = document.getElementById(&#39;searchModal&#39;);
                const overlay = document.querySelector(&#39;.search-modal-overlay&#39;);

                openButtons.forEach(function (btn) {
                    btn.addEventListener(&#39;click&#39;, function () {
                        modal.style.display = &#39;flex&#39;;
                    });
                });

                if (closeBtn) {
                    closeBtn.addEventListener(&#39;click&#39;, function () {
                        modal.style.display = &#39;none&#39;;
                    });
                }

                // Close on ESC key
                document.addEventListener(&#39;keydown&#39;, function (e) {
                    if (e.key === &#34;Escape&#34;) {
                        modal.style.display = &#39;none&#39;;
                    }
                });

                // Close when clicking outside content
                if (overlay) {
                    overlay.addEventListener(&#39;click&#39;, function (e) {
                        if (e.target === overlay) {
                            modal.style.display = &#39;none&#39;;
                        }
                    });
                }
            });
        </script>
      </div>
    </header>
    <!-- header end here -->
    <style>
      .header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        z-index: 1000;
        background-color: #FAFDFF;
        transition: transform 0.3s ease, opacity 0.3s ease;
    }

    .header--hidden {
        transform: translateY(-100%);
        opacity: 0;
    }

    .header--visible {
        transform: translateY(0);
        opacity: 1;
    }
    

   body &gt; section:first-of-type {
        padding-top: 150px; /* Prevent content from hiding under header */
    }
     section.contact.Desktop {
        padding-top: 150px !important; /* Prevent content from hiding under header */
    }
    </style>
    <script>
      document.addEventListener(&#34;DOMContentLoaded&#34;, function () {
        const header = document.querySelector(&#34;.header&#34;);
        let lastScroll = 0;

        window.addEventListener(&#34;scroll&#34;, function () {
            const currentScroll = window.pageYOffset;

            if (currentScroll &lt;= 0) {
                header.classList.remove(&#34;header--hidden&#34;);
                return;
            }

            if (currentScroll &gt; lastScroll) {
                // Scrolling down
                header.classList.remove(&#34;header--visible&#34;);
                header.classList.add(&#34;header--hidden&#34;);
            } else {
                // Scrolling up
                header.classList.remove(&#34;header--hidden&#34;);
                header.classList.add(&#34;header--visible&#34;);
            }

            lastScroll = currentScroll;
        });
    });
    </script>
    <!-- Home Page Component -->
    <section class="banner">
      <div class="container">
        <div class="main__banner">
          <div class="banner_img">
            <div style="position: absolute; width: 100%; height: 100%; background: #00000054;">
            </div>
            <img src="https://perstarke-webdev.de//storage/680/banner2.webp" alt="" class="img__cover" alt="Website banner" width="1920" height="600" />
          </div>
          <div class="banner__mainContent">
            <div class="banner_topContent">
              <h1>
                OneFlow Jekyll
                <span></span>
                <br />
                <b>                Theme Documentation
</b>
              </h1>
            </div>
            <div class="banner_bottomContent ">
              <h2>
                Crafting effortless
                <br />
                One-Pager Websites
              </h2>
              <div class="banner_btn">
                <a href="https://github.com/perstarke-webdev/oneflow-jekyll-theme?tab=readme-ov-file#oneflow-jekyll-theme" target="_blank" class="themebtn themebtn--blutrns">                Get the theme
</a>
                <a href="https://oneflow-jekyll-theme.github.io/" class="themebtn themebtn--blutrns" target="_blank" class="themebtn themebtn--blutrns">                Theme website
</a>
                <a href="https://oneflow-jekyll-theme-example-one.github.io/" target="_blank" class="themebtn themebtn--blutrns">                First example website
</a>
                <a href="https://oneflow-jekyll-theme-example-two.github.io/" target="_blank" class="themebtn themebtn--blutrns">                Second example website
</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Home Partner -->
    <!-- Home Page Component -->
    <section class="OneFlow">
      <div class="container">
        <div class="mainOneFlow">
          <h1 id="what-it-is">
            What it is
          </h1>
          OneFlow is a Jekyll Theme designed to create
          <b class="light-color">          stunning, clear and practical modern One-Pager Websites
</b>
          . It offers lots of
            features and customization options, so you can easily create a Site that matches your own or your client&#39;s
            wishes for design and structure.
          <br />
          <br />
          It offers
          <b class="light-color">          various customization
                options
</b>
          , like a sticky or non-sticky navigation bar and several diverse color skins. Furthermore,
            OneFlow comes with lots of build-in utilities like buttons, boxes, notices, galleries, round-images and
            image-text-rows. You can apply sections with alternating background color and can fuss-freely use a
            background image.
          <br />
          <br />
          It is
          <b class="light-color">          straightforward and easy to use
</b>
          . You just need
            to clone the
          <a href="https://github.com/perstarke-webdev/oneflow-jekyll-theme" rel="noopener noreferrer nofollow" target="_blank">          GitHub Repository and can get started straightaway.
</a>
          <br />
          <br />
          <div>
            <h3>
              Table of Contents
            </h3>
            <ul>
              <li>
                <a href="#what-it-is">                What it is
</a>
              </li>
              <li>
                <a href="#getting-started">                Getting started &amp; development
</a>
              </li>
              <li>
                <a href="#html-and-md">                Markdown and HTML
</a>
              </li>
              <li>
                <a href="#responsive-design">                Responsive Design
</a>
              </li>
              <li>
                <a href="#license">                License &amp; credits
</a>
              </li>
              <li>
                <a href="#start-editing">                Start editing your Site
</a>
                <ul>
                  <li>
                    <a href="#basic-setup">                    Content &amp; Basic home page setup
</a>
                    <ul>
                      <li>
                        <a href="#skins">                        Color skins
</a>
                      </li>
                      <li>
                        <a href="#masthead">                        Masthead
</a>
                        <ul>
                          <li>
                            <a href="#nav">                            Navigation
</a>
                          </li>
                        </ul>
                      </li>
                      <li>
                        <a href="#background">                        Background
</a>
                      </li>
                      <li>
                        <a href="#popup">                        Popup
</a>
                      </li>
                      <li>
                        <a href="#sections">                        Sections
</a>
                      </li>
                      <li>
                        <a href="#utilities">                        Utilities
</a>
                        <ul>
                          <li>
                            <a href="#notices">                            Notices
</a>
                          </li>
                          <li>
                            <a href="#boxes">                            Boxes
</a>
                          </li>
                          <li>
                            <a href="#buttons">                            Buttons
</a>
                          </li>
                          <li>
                            <a href="#videos">                            Responsive video-embed
</a>
                          </li>
                          <li>
                            <a href="#galleries">                            Galleries
</a>
                          </li>
                          <li>
                            <a href="#rounded-images">                            Rounded images
</a>
                          </li>
                          <li>
                            <a href="#itr">                            Image-text-rows
</a>
                          </li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="#footer">                    Footer
</a>
                  </li>
                  <li>
                    <a href="#custom-styles">                    Custom styles
</a>
                  </li>
                  <li>
                    <a href="#fonts">                    Fonts
</a>
                  </li>
                  <li>
                    <a href="#icons">                    Icons
</a>
                  </li>
                  <li>
                    <a href="#editables">                    Editables
</a>
                  </li>
                  <li>
                    <a href="#customize">                    Further customization
</a>
                  </li>
                </ul>
              </li>
              <li>
                <a href="#support">                Support / Contact
</a>
              </li>
              <li>
                <a href="#contribution">                Contribution
</a>
              </li>
              <li>
                <a href="#share-results">                Share your experience and results
</a>
              </li>
            </ul>
          </div>
          <hr class="big-sep" />
          <h1 id="getting-started">
            Getting started &amp; development
          </h1>
          <h3>
            Fork and clone the repository
          </h3>
          The
          <b class="light-color">          vision of this theme
</b>
          is
          <b class="light-color">          simplicity and accessibility
</b>
          , to easily create stunning websites from scratch.
            Therefore, it&#39;s not available as a classic gem-based Jekyll theme, but as a ready-to-use GitHub repository
            that you just need to fork and clone. So, get ahead and make a fork of this repository, rename it if you
            like to suit the name of the site you want to create, locally clone it, and directly start editing!
          <h3>
            How
                to start a development docker container
          </h3>
          To test your website and see all of your changes in
            real-time without deploying it online, you can easily build your site locally. OneFlow comes with build-in
            docker configuration using
          <a href="https://github.com/BretFisher/jekyll-serve" rel="noopener noreferrer nofollow" target="_blank">          BretFisher&#39;s jekyll serve
</a>
          .
          <ul>
            <li>
              Make sure you have
              <a rel="noopener noreferrer nofollow" target="_blank" href="https://bundler.io/">              Bundler
</a>
              and
              <a rel="noopener noreferrer nofollow" target="_blank" href="https://www.docker.com/">              Docker
</a>
              installed
            </li>
            <li>
              Open up a terminal, navigate to your local repository, and run
              <code>              docker compose up
</code>
              .
            </li>
          </ul>
          Your site will then be visible at
          <i>          http://0.0.0.0:4000/
</i>
          in any browser.
          <hr class="big-sep" />
          <h1 id="html-and-md">
            Markdown and HTML
          </h1>
          Use raw and flexible HTML or clear markdown to write your
            content. Markdown is rendered with
          <a href="https://kramdown.gettalong.org/" rel="noopener noreferrer nofollow" target="_blank">          kramdown
</a>
          , which supports applying css classes to
            the Markdown. That means, you can add notices, boxes and other utilities even to your Markdown content, as
            simple as
          <code>          &#34;Text you want to add the classes to {: .class1 .class2}&#34;
</code>
          . This documentation will
            show everything in HTML, but as shown in the lines above, applying css classes is also easily possible with
            Markdown.
          <hr class="big-sep" />
          <h1 id="responsive-design">
            Responsive Design
          </h1>
          All of OneFlows features are 100% responsive and adapt to
            different screen sizes, so your site looks good on all devices!
          <hr class="big-sep" />
          <h1 id="license">
            License &amp; Credits
          </h1>
          <h3>
            License
          </h3>
          OneFlow is Open-Source and licensed under the
          <a href="https://opensource.org/license/mit/" rel="noopener noreferrer nofollow" target="_blank">          MIT License
</a>
          . That means, you can freely copy,
            use and customize it - whatever you like! You do not need to give credits to me (the creator), but of course
            I&#39;m happy if you do. But don&#39;t feel obliged to do so.
          <h3>
            Credits
          </h3>
          OneFlow is based on the
          <a href="https://github.com/mmistakes/minimal-mistakes" rel="noopener noreferrer nofollow" target="_blank">          Minimal Mistakes Theme
</a>
          . Minimal Mistakes has been used as a starting point for
            OneFlow. Credits to it&#39;s creator, Michael Rose, for the awesome and versatile theme he created!
          <hr class="big-sep" />
          <h1 id="start-editing">
            Start editing your Site
          </h1>
          The main parts you want to edit are:
          <ul>
            <li>
              <code>              README.md
</code>
              for the readme of your repository,
            </li>
            <li>
              <code>              /_data/navigation.yml
</code>
              for the navigation links,
            </li>
            <li>
              <code>              /_pages/index.html
</code>
              for your main content,
            </li>
            <li>
              <code>              /_pages/imprint.html
</code>
              for the imprint &amp; privacy note,
            </li>
            <li>
              <code>              _config.yml
</code>
              for the basic setup of your site,
            </li>
            <li>
              <code>              /assets/images
</code>
              for all images and graphics you use on your site,
            </li>
            <li>
              <code>              /assets/css/custom-styles.css
</code>
              if you want to add custom css styles,
            </li>
            <li>
              <code>              /assets/fonts
</code>
              if you want to add custom fonts and
            </li>
            <li>
              <code>              /_includes/editables
</code>
              if you create a website for a client who regularly wants to change
                    parts of the site him/herself.
            </li>
          </ul>
          <h2 id="skins">
            Color skins
          </h2>
          OneFlow comes with 10 diverse color skins you can easily apply. These are:
          <i>          default
</i>
          ,
          <i>          air
</i>
          ,
          <i>          aqua
</i>
          ,
          <i>          contrast
</i>
          ,
          <i>          dark
</i>
          ,
          <i>          dirt
</i>
          ,
          <i>          neon
</i>
          ,
          <i>          mint
</i>
          ,
          <i>          plum
</i>
          and
          <i>          sunrise
</i>
          . Check the
          <a href="https://github.com/mmistakes/minimal-mistakes?tab=readme-ov-file#skins-color-variations" rel="noopener noreferrer nofollow" target="_blank">          Minimal Mistakes documentation about color skins
</a>
          for example images. Define your preferred skin by changing the value of
          <code>          oneflow-skin
</code>
          in
          <code>          _config.yml.
</code>
          .
          <h2 id="masthead">
            Masthead
          </h2>
          The Masthead, including the navigation bar,
            offers a few customization options. All of this configuration can be done in
          <code>          config.yml
</code>
          .
          <br />
          <br />
          First, you can decide whether you like it to be
          <b class="light-color">          sticky
</b>
          , meaning it will stay visible on top of the page even when you scroll
            down, or not. To make the masthead sticky, set
          <code>          sticky-masthead: true
</code>
          .
          <br />
          <br />
          You can
            furthermore easily set the
          <b class="light-color">          opacity
</b>
          of the masthead with
          <code>          masthead-opacity:
                xxx
</code>
          , where xxx is a number between 0 and 1. A good starting point that works good for most sites
            is 0.8 to 0.9.
          <br />
          <br />
          The masthead can either contain a
          <b class="light-color">          logo (or any other
                image)
</b>
          , or your site title and optionally a sub-title. If you want to display your logo / image
            there, set
          <code>          logo: /assets/images/logo.webp
</code>
          or the respective path to the image and filetype you
            want to use. If you don&#39;t want your logo / image there, remove the logo path or out-comment it by setting
          <code>          #
</code>
          behind the
          <code>          :
</code>
          like so:
          <code>          logo: #/assets/...
</code>
          . By default, the site
            title, which is also shown in the browser tab, is then displayed instead of the logo. You can set the title
            by setting
          <code>          title: &#34;your-website-title&#34;
</code>
          . Set the subtitle with
          <code>          subtitle:
                &#34;your-subtitle&#34;
</code>
          or set this to
          <code>          &#34;&#34;
</code>
          to have no subtitle. If you want to display a
            different title than your default site title in the masthead, you can set this with
          <code>          masthead_title:
                &#34;your-masthead-title&#34;
</code>
          . Set this to
          <code>          &#34;&#34;
</code>
          to display no title.
          <h3 id="nav">
            Navigation
          </h3>
          To edit the links in the navigation bar, head over to
          <code>          /_data/navigation.yml
</code>
          . Unter the
            main-variable, you can set the title and url each nav link should point to. For linking to a section on the
            main page, include a &#34;#&#34; before the id, and set the id-attribute within the section-tag or the header-tag of
            that section. For external links, you can set blank to true, so the page opens in a new tab, and as URL
            include the full url with https:// at the beginning.
          <h2 id="background">
            Background
          </h2>
          As the background
            for your site, you can either stick with the background colors that come with your chosen color skin, or you
            can apply a
          <b class="light-color">          background image
</b>
          instead. Background image settings are all done in
          <code>          config.yml
</code>
          . Set
          <code>          background-image: &#34;/path/to/your/background-image.webp&#34;
</code>
          . To have
            no background-image, remove or out-comment this line. When working with a background image, it is strongly
            recommended to use a horizontal background image for the desktop version of your site and an upright image
            for the mobile version. You can easily do this, by using a horizontal image for
          <code>          background-image
</code>
          , and setting a different image (or different version of the same image) for
          <code>          background-image-mobile
</code>
          . Furthermore, it is also strongly recommended to apply a slightly
            transparent overlay to the background image, for better readability of all texts on your site. You can set
            this by setting
          <code>          background-image-overlay : rgba(255, 255, 255, 0.5)
</code>
          or any other rgba color
            value you like.
          <h2 id="popup">
            Popup
          </h2>
          As some countries, like Germany, require
          <b class="light-color">          information and consent about cookie-usage
</b>
          and the usage of a CDN for example
            for deploying sites on GitHub pages, OneFlow comes with a build-in Popup for that purpose. You can enable or
            disable the Popup in
          <code>          config.yml
</code>
          with true/false for
          <code>          show-popup
</code>
          . Do not use
            quotation marks for setting true/false values in the configuration file.
          <br />
          <br />
          The existing version of
            the popup is a suggestion and should (no legal advice given) fulfill german laws regarding cookie and
            cdn-usage consent.
          <br />
          <br />
          To edit the content of the popup, navigate to
          <code>          /_includes/popup.html
</code>
          and edit its HTML. This file also contains a script-tag with the javascript for the popup. This script sets
            a cookie for one day, when the user clicks on the &#34;Agree&#34;-button, so the popup is not displayed on every
            page reload, but only after one day. Edit the line
          <code>          expiresDate.setDate(expiresDate.getDate() +
                1);
</code>
          to set this to a different time interval.
          <h2 id="basic-setup">
            Content &amp; Basic home page
                setup
          </h2>
          To start adding content to your main page, navigate to
          <code>          /_pages/index.html
</code>
          .
            Remove the example content, and start adding your own!
          <br />
          <br />
          First, you need to set some basics in the
            YAML front matter. So, start with:
          <br />
          <code>          ---
          <br />
          layout: page
          <br />
          title: &#34;The Title That Should Display In Your Page Hero&#34;
          <br />
          excerpt: &#34;The
                Sub-Title Below Your Main Title&#34;
          <br />
          permalink: /
          <br />
          ---
</code>
          <br />
          <br />
          You can furthermore customize
            the
          <b class="light-color">          Page Hero
</b>
          , which is the first thing catching the visitors eyes! The Page Hero
            can include:
          <ul>
            <li>
              A title
            </li>
            <li>
              A subtitle
            </li>
            <li>
              An image
            </li>
            <li>
              An image overlay
            </li>
            <li>
              A caption
            </li>
            <li>
              Action buttons
            </li>
          </ul>
          Set and customize them like so:
          <br />
          <code>          header:
          <br />
          overlay_image: /assets/images/header.webp
          <br />
          overlay_filter: rgba(0, 0, 0, 0.6)
          <br />
          caption: &#34;Photo
                by **[Text](Link)**&#34;
          <br />
          actions:
          <br />
          -
                label: &#34;Get Started&#34;
          <br />
          url:
                &#34;https://url-to-link-to.com&#34;
          <br />
          blank: true
</code>
          <br />
          <br />
          Captions and labels support Markdown. You can add as many
          <b class="light-color">          action
                buttons
</b>
          as you like. The have a label, a URL and a &#34;blank&#34;-characteristic. Blank is either true or
            false and determines, whether the link opens up in a new tab or not. If this is true, the HTML a-tag
            contains
          <code>          target=&#34;_blank&#34;
</code>
          as well as
          <code>          rel=&#34;noopener noreferrer nofollow&#34;
</code>
          , which is
            important so that opening link in a new tab doesn&#39;t come with security and SEO impairments.
          <br />
          <br />
          Remember that indentation is important for the YAML front matter.
          <h2 id="sections">
            Sections
          </h2>
          OneFlow
            offers
          <b class="light-color">          alternating colored sections
</b>
          .
          <br />
          <br />
          If you do not want alternating
            colors, there is no need to apply any section tags, just write all of your content outside of any section
            tags. To separate different parts of your page, you can drop in a nicely styled big
          <b class="light-color">          separation line
</b>
          easily with
          <br />
          <code>          <hr class="section-sep" />
</code>
          . You can use this both with and without alternating colored
            sections.
          <br />
          <br />
          To apply alternating colored sections, do the following:
          <br />
          Wrap every section that
            should be normally colored in
          <br />
          <code>          <section class="site-section" id="section-2">
            <br />
            // Content within the section
            <br />
          </section>
</code>
          <br />
          For every alternatively colored section, add the class
          <code>          alternative-color
</code>
          to the section.
          <br />
          <h4>
            Some notes about that:
          </h4>
          Alternatively colored sections don&#39;t look too good before the footer. So, it
            is recommended to always let the last section of your site be a normally colored one.
          <br />
          Furthermore, if
            you want the first section of your site to be an alternatively colored one, also add the class
          <code>          first-section
</code>
          to it. This makes sure the color starts directly below the Page Hero, and there
            is no small space in a different color in between Page Hero and first section.
          <h2 id="utilities">
            Utilities
          </h2>
          Of course, OneFlow comes with build-in styles for normal Markdown/HTML tags like headers, paragraphs,
            anchor-tags (links) and so on. There are furthermore some utilities that you can use to organize and style
            your content in a good-looking and structured way. Check out the
          <a href="https://oneflow-jekyll-theme.github.io/" rel="noopener noreferrer nofollow" target="_blank">          theme
                website
</a>
          to see example of all of these utilities!
          <h3 id="notices">
            Notices
          </h3>
          Notices highlight a
            paragraph or a div. Just add the
          <code>          notice
</code>
          class to any element, easy as that.
          <br />
          Apart from the
            standard-notice, there are some others with different colors, which are:
          <ul>
            <li>
              <code>              notice--primary
</code>
            </li>
            <li>
              <code>              notice--success
</code>
            </li>
            <li>
              <code>              notice--warning
</code>
            </li>
            <li>
              <code>              notice--danger
</code>
            </li>
            <li>
              <code>              notice--info
</code>
            </li>
          </ul>
          Apply these classes, instead of the notice-class, to use the different colors.
          <h3 id="boxes">
            Boxes
          </h3>
          Boxes also highlight your content, but with a different styling. Just apply the
          <code>          box
</code>
          class
            to any div-element to put it into a box with a nice little rounded border and very subtle background. Just
            as notices, boxes offer the same color variations. Keep the box-class with your divs and add one of the
            following:
          <ul>
            <li>
              <code>              box--primary
</code>
            </li>
            <li>
              <code>              box--success
</code>
            </li>
            <li>
              <code>              box--warning
</code>
            </li>
            <li>
              <code>              box--danger
</code>
            </li>
            <li>
              <code>              box--info
</code>
            </li>
          </ul>
          Boxes furthermore can be put into a div with the class
          <code>          box-container
</code>
          . Within that
            container, you can apply the
          <code>          box-half
</code>
          class to make a box fill half of the width and therefore
            be able to fit 2 boxes next to each other, or the
          <code>          box-third
</code>
          class to make a box fill a third of
            the width and therefore be able to fit 3 boxes next to each other. On small screens, boxes stack below each
            other responsively.
          <h3 id="buttons">
            Buttons
          </h3>
          Add the
          <code>          btn
</code>
          class plus any of the following
            classes to any a-tag to style the link as a button:
          <ul>
            <li>
              <code>              btn--primary
</code>
            </li>
            <li>
              <code>              btn--success
</code>
            </li>
            <li>
              <code>              btn--warning
</code>
            </li>
            <li>
              <code>              btn--danger
</code>
            </li>
            <li>
              <code>              btn--info
</code>
            </li>
            <li>
              <code>              btn--inverse
</code>
            </li>
          </ul>
          You can furthermore edit the size of the button with the following classes:
          <ul>
            <li>
              <code>              btn--x-large
</code>
            </li>
            <li>
              <code>              btn--large
</code>
            </li>
            <li>
              <code>              btn--small
</code>
            </li>
          </ul>
          <h3 id="videos">
            Responsive video-embed
          </h3>
          Embed a video from YouTube, Vimeo, Google Drive, or bilibili
            that responsively sizes to fit the width of its parent. This feature is taken un-edit from Minimal Mistakes,
          <a href="https://mmistakes.github.io/minimal-mistakes/docs/helpers/#responsive-video-embed" rel="noopener noreferrer nofollow" target="_blank">          see the Minimal Mistakes Docu about responsive video
                embed here
</a>
          .
          <h3 id="galleries">
            Galleries
          </h3>
          The gallery is as well taken from Minimal Mistakes,
            slightly edited in style to better fit OnePager Websites.
          <a href="https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery" rel="noopener noreferrer nofollow" target="_blank">          Check the Minimal Mistakes Docu about galleries here
</a>
          .
          <h3 id="rounded-images">
            Rounded images
          </h3>
          Rounded images are a cool helper that displays a circular
            image in the top of a box, so that you can add header and a caption below the image. They add a cool visual
            element and can provide good structure as well. They can be included easily via YAMl front matter. Set the
            front matter like so:
          <br />
          <code>          round-images:
          <br />
          - image-path: &#34;/assets/images/image.webp&#34;
          <br />
          size: &#34;full&#34;
          <br />
          header: &#34;text for the header&#34;
          <br />
          caption: &#34;text for the caption&#34;
          <br />
</code>
          <br />
          You can include further rounded image boxes by adding a next &#34;- image-path&#34; and all other
            necessary variables. Size can be either &#34;full&#34;, &#34;half&#34; or &#34;third&#34; and determines, how much of the page width
            the box with the rounded image is going to take. With half, two boxes fit next to each other, with third,
            it&#39;s three.
          <br />
          Include the rounded images anywhere with
          <code>          {% include rounded-images
                %}
</code>
          .
          <br />
          You can use any other name than &#34;round-images&#34; for the rounded images. Then, you
            need to include an id in the include, like so:
          <code>          {% include rounded-images id=&#34;id-you-chose&#34;
                %}
</code>
          .
          <br />
          Half or third boxes stack below each other responsively on smaller screens.
          <h3 id="itr">
            Image-text-rows
          </h3>
          Image-text-rows include an image either on the left or right side, and a
            header + caption on the other side. They optionally can include a button with a link.
          <br />
          They can be set
            via YAMl front matter, and offer huge customization options. Create them like so:
          <br />
          <code>          image-text-row:
          <br />
          - header: &#34;text for the header&#34;
          <br />
          excerpt: &#34;text for the caption/excerpt&#34;
          <br />
          btn-url: &#34;https://your-url.com&#34;
          <br />
          btn-class: &#34;primary/success/...&#34;
          <br />
          btn-label: &#34;label
                for the button&#34;
          <br />
          blank: false
          <br />
          image-url:
                &#34;/assets/images/image.webp&#34;
          <br />
          alt-text: &#34;alternative text for the image&#34;
          <br />
          image-width &#34;400px&#34;
          <br />
          image-right: true
</code>
          <br />
          Leave out btn-url and the other btn-variables to not include a button.
          <br />
          &#34;Blank&#34; determines whether the
            link from the button is opened in a new tab or not.
          <br />
          &#34;Image-right&#34; sets whether the image is on the
            right side. With true, it is, with false, it is left.
          <br />
          Image and text responsively stack below each
            other on smaller screens, with the image always on top.
          <h2 id="footer">
            Footer
          </h2>
          You can easily customize
            the footer in
          <code>          config.yml
</code>
          . Under
          <code>          footer links
</code>
          you can set the social links that you
            want to include in the footer. Just set the
          <code>          url
</code>
          attribute for every social link you want to
            include, and out-comment the url attribute for every social link that you do not want to include.
          <br />
          Furthermore, you can set
          <code>          copyright
</code>
          to anything you like, like your or your clients name, which
            will display in the footer as &#39;© [year] [name]&#39;&#34;, with &#39;year&#39; and &#39;name&#39; being replaced by the respective
            values.
          <br />
          Also, you can include a
          <code>          creator
</code>
          name and url, if you like, which will then display
            in the footer as &#34;Created by&#34;. If you remove or out-comment the creator attributes, no &#34;Created by&#34; will be
            shown.
          <h2 id="custom-styles">
            Custom styles
          </h2>
          If you want to add your own custom css, you can do that in
            the ready-to-use
          <code>          custom-styles.css
</code>
          file that is located with in
          <code>          /assets/css
</code>
          . Just
            add your css in there, nothing else you need to do as setup.
          <h2 id="fonts">
            Fonts
          </h2>
          Just like Minimal
            Mistakes, OneFlow uses system fonts for all font stacks, to provide a clean look and to improve performance.
            More information about that in the
          <a href="https://mmistakes.github.io/minimal-mistakes/docs/stylesheets/#font-stacks" rel="noopener noreferrer nofollow" target="_blank">          Minimal Mistakes Docu about Fonts
</a>
          .
          <br />
          Furthermore, you can easily apply custom fonts within OneFlow.
          <a href="https://fonts.google.com/" rel="noopener noreferrer nofollow" target="_blank">          Google Fonts
</a>
          offer high versatility and are free
            to use (you just might need to include a license, depending on the font). They can be hosted locally with
            ease. I recommend using
          <a href="https://gwfh.mranftl.com/fonts." rel="noopener noreferrer nofollow" target="_blank">          Google Webfonts Helper
</a>
          for that. Select the font and font-styles you want there,
            download the files, and place them in
          <code>          /assets/fonts
</code>
          . Then open up
          <code>          /_sass/oneflow/_fonts.scss
</code>
          and put the css you got from Google Webfonts Helper there. That&#39;s
            it, you now host the font locally and can apply it to any text you like.
          <h2 id="icons">
            Icons
          </h2>
          OneFlow
            comes with build-in support for
          <a href="https://fontawesome.com/" rel="noopener noreferrer nofollow" target="_blank">          Font Awesome Icons
</a>
          . Font Awesome 6.5.1 is included and hosted locally within
            OneFlow. Nothing for you to do but apply the icons! Just add an i-tag with the respective classes, check out
            the Font Awesome Website to find all their icons.
          <h2 id="editables">
            Editables
          </h2>
          As a Web Developer,
            especially for private customers or small companies, I&#39;ve came across the following situation a few times:
            The
          <b class="light-color">          client wants to edit parts of the website him/herself regularly
</b>
          , for example
            to add or delete upcoming events or dates. Large companies can pay web developers for that, but private
            customers or small companies often understandably can&#39;t afford long-term maintenance costs.
          <br />
          To make
            this as easy as possible, utilize the editables-feature from OneFlow! Put any HTML/Markdown part that the
            client needs to edit in a separate file and place this file in the
          <code>          /_includes/editables
</code>
          folder,
            then include it on the main page with
          <code>          {% include /editables/filename.html %}
</code>
          .
          <br />
          The client then only needs to make changes within the given file, which makes it as as simple and as little
            error-prone as possible.
          <h2 id="customize">
            Further customization
          </h2>
          OneFlow offers huge customization
            options without the need to touch any of the layouts, includes or sass files. If you need even further
            customization, these directories and files are included in the GitHub Repository, so you can go ahead and
            edit all files in every way you want for further customization and fine-granular styling. The layout
            structure can be edited within
          <code>          /_layouts/default.html or page.html
</code>
          . The scss stylesheets are
            located within the
          <code>          /_sass
</code>
          directory, and includes like the page hero, footer, masthead and also
            utilities like the gallery, rounded images or image-text-rows are located within the
          <code>          /_includes
</code>
          folder and can be edited right there.
          <h2 id="support">
            Support / Contact
          </h2>
          If you have any questions or
            feedback, don&#39;t hesitate to contact me! You can reach me via Email:
          <a href="mailto: info@perstarke-webdev.de">          info@perstarke-webdev.de
</a>
          ,
          <a href="https://www.instagram.com/per.starke/">          Instagram
</a>
          or by writing a
          <a href="https://github.com/perstarke-webdev/oneflow-jekyll-theme/issues">          GitHub Issue in the OneFlow
                Repository
</a>
          .
          <h2 id="contribution">
            Contribution
          </h2>
          If you have any suggestions on how to improve
            OneFlow, I appreciate any Pull Requests or Issues on GitHub. Feel free to contribute in any way!
          <h2 id="share-results">
            Share your experience and results
          </h2>
          If you created a Website using OneFlow, I am
            very happy to see and share the results! Message me, or create a Pull Request where you link your Website in
            the ReadMe of the OneFlow Repository.
          <h>
            Happy website crafting y&#39;all!
          </h>
        </div>
      </div>
    </section>
    <!--editor-->
    <footer class="footer">
      <div class="container">
        <div class="main_footer">
          <div class="footer_startMain row">
            <div class="footer_start col-md-6 col-lg-6 py-4">
              <h3>
                Ready to Start Your Web Momentum?
              </h3>
              <p>
                Web development, reimagined – by people who care.
              </p>
              <div class="footer_btn">
                <a href="/contact-us" class="themebtn">                Let’s build Your Website
</a>
              </div>
            </div>
            <div class="footer_newsLetter col-md-6 col-lg-4 py-4">
              <p>
                Join the Web Momentum! Stay in the loop with exclusive updates, launches, and insights – no spam, just real value for your journey.
              </p>
              <form action="https://perstarke-webdev.de/store-news" method="post" class="news_form" onsubmit="showMessage(event)">
                <input type="hidden" name="_token" value="IYlLTKflz3rz8oKFKQRObuDaVKC5DsHzGpZKLrRU" autocomplete="off" />
                <div class="inputFeild">
                  <input type="email" name="email" placeholder="Email address" required="" />
                </div>
                <div class="label_feild">
                  <input type="checkbox" id="update" required="" />
                  <label for="update">
                    I want to receive email updates from PSWD
                  </label>
                </div>
                <div class="field_btn">
                  <button type="submit" class="themebtn themebtn--blk">
                    Send
                  </button>
                </div>
                <p id="formSuccessMessage" style="display:none; margin-top: 15px; color: #bff990;">
                  Welcome to Web Momentum – please check your Emails
                </p>
              </form>
              <script>
                function showMessage(e) {
                                e.preventDefault(); // stop default form submit
                            
                                const form = e.target;
                                const formData = new FormData(form);
                            
                                fetch(form.action, {
                                    method: &#34;POST&#34;,
                                    body: formData,
                                    headers: {
                                        &#39;Accept&#39;: &#39;application/json&#39;
                                    }
                                })
                                .then(response =&gt; response.json())
                                .then(data =&gt; {
                                    if (data.success) {
                                        form.reset();
                                        document.getElementById(&#34;formSuccessMessage&#34;).style.display = &#34;block&#34;;
                                    } else {
                                        alert(&#34;Something went wrong. Please try again.&#34;);
                                    }
                                })
                                .catch(() =&gt; alert(&#34;Network error. Please try later.&#34;));
                            }
              </script>
            </div>
          </div>
          <div class="footer_contact">
            <div class="footer_contactMain">
              <h4>
                Per Starke
              </h4>
              <ul class="foo_contList">
                <li>
                  <a href="mailto:info@perstarke-webdev.de">                  info@perstarke-webdev.de
</a>
                </li>
                <li>
                  <a href="https://wa.link/pswd" target="_blank" rel="noopener noreferrer nofollow">                  +49 160 93268817
</a>
                </li>
              </ul>
            </div>
            <div class="grab_para">
              <h6>
                And grab some good coffee – it’s on us. 😉
              </h6>
            </div>
          </div>
          <div class="footer_bottom">
            <ul class="footer_socialIcons">
              <li>
                <a href="https://www.instagram.com/pswd.studio/" target="_blank" rel="noopener noreferrer nofollow" aria-label="Instagram">                <i class="bx bxl-instagram"></i>
</a>
              </li>
              <li>
                <a href="https://www.linkedin.com/company/per-starke-web-development/" target="_blank" rel="noopener noreferrer nofollow" aria-label="linkedin">                <i class="bx bxl-linkedin"></i>
</a>
              </li>
              <li>
                <a href="/imprint" target="_blank" aria-label="imprint">                <i class="fa-solid fa-gavel"></i>
</a>
              </li>
              <!-- <li><a href="https://github.com/perstarke-webdev"><i class='bx bxl-github'></i></a></li>
                    <li><a href="https://medium.com/@perstarke"><i class="medium">M</i></a></li>
                    <li><a href="https://dev.to/per-starke-642"><i class='bx bxl-dev-to'></i></a></li> -->
            </ul>
            <p style="    text-align: center;">
              <span style="color: rgb(255, 255, 255); font-family: Inter, sans-serif; background-color: rgb(15, 21, 29);">              Copyright ©PSWD - Collaboration with
</span>
              <a href="https://www.tra-ng.de/" target="_blank" rel="noopener noreferrer nofollow" style="padding: 0px; margin: 0px; list-style-type: none; font-family: Inter, sans-serif; color: rgb(255, 255, 255); display: inline-block; transition: 300ms ease-in-out; background-color: rgb(15, 21, 29); text-decoration-line: underline !important;">              Trang Studios
</a>
              <span style="color: rgb(255, 255, 255); font-family: Inter, sans-serif; background-color: rgb(15, 21, 29);">              &amp;
</span>
              <a href="https://studiomaller.com/" target="_blank" rel="noopener noreferrer nofollow" style="padding: 0px; margin: 0px; list-style-type: none; font-family: Inter, sans-serif; color: rgb(255, 255, 255); display: inline-block; transition: 300ms ease-in-out; background-color: rgb(15, 21, 29); text-decoration-line: underline !important;">              Studio Maller
</a>
            </p>
          </div>
        </div>
      </div>
    </footer>
    <!-- Core JS -->
    <script src="https://perstarke-webdev.de/assets_frontend/assets/js/jquery.js">
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/toastr.js/latest/toastr.min.js">
    </script>
    <script src="https://perstarke-webdev.de/assets_frontend/assets/js/bootstrap.bundle.min.js">
    </script>
    <script src="https://perstarke-webdev.de/assets_frontend/assets/js/slick.js">
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js">
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tilt.js/1.2.1/tilt.jquery.min.js">
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.ripples/0.5.3/jquery.ripples.js">
    </script>
    <script src="https://perstarke-webdev.de/assets_frontend/assets/js/app.js">
    </script>
    <script defer="" data-domain="perstarke-webdev.de" src="https://plausible.io/js/script.js">
    </script>
    <script>
      if (!localStorage.getItem(&#34;cookieFreeAccepted&#34;)) {
    const banner = document.createElement(&#34;div&#34;);
    banner.style.cssText =
        &#34;position:fixed;bottom:0;left:0;right:0;background:#4A64F6;color:#fff;&#34; +
        &#34;padding:12px 20px;font-size:14px;text-align:center;z-index:9999;&#34; +
        &#34;display:flex;flex-direction:column;align-items:center;&#34;;
    banner.innerHTML =
        &#39;&lt;span&gt;This website is &lt;strong&gt;cookie-free&lt;/strong&gt; for your privacy.&lt;/span&gt;&#39; +
        &#39;&lt;small style=&#34;font-size:12px;opacity:.8;margin-top:4px;&#34;&gt;&#39; +
        &#39;(Calendly may show its own cookie banner)&lt;/small&gt;&#39; +
        &#39;&lt;button id=&#34;cookieFreeAccept&#34; style=&#34;margin-top:10px;background:#fff;color:#4A64F6;&#39; +
        &#39;border:none;padding:6px 12px;font-weight:bold;border-radius:4px;&#34;&gt;Okay&lt;/button&gt;&#39;;
    document.body.appendChild(banner);
    document.getElementById(&#34;cookieFreeAccept&#34;).onclick = function(){
        localStorage.setItem(&#34;cookieFreeAccepted&#34;,&#34;true&#34;);
        banner.remove();
    };
}
    </script>
    <script>
      var cta = document.querySelector(&#34;.cta-btn&#34;);
if (cta) {
    cta.addEventListener(&#34;click&#34;, function () {
        alert(&#34;Thanks for connecting! 🚀 We&#39;ll reach out soon.&#34;);
    });
}
    </script>
    <script>
      const points = document.querySelectorAll(&#34;.pain-points li&#34;);
const solutionBox = document.querySelector(&#34;.solution&#34;);

window.addEventListener(&#34;scroll&#34;, function () {
    let trigger = window.innerHeight * 0.85;
    points.forEach((p,i)=&gt;{
        if (p.getBoundingClientRect().top &lt; trigger) {
            setTimeout(()=&gt;p.classList.add(&#34;show&#34;), i*200);
        }
    });
    if (solutionBox &amp;&amp; solutionBox.getBoundingClientRect().top &lt; trigger) {
        solutionBox.classList.add(&#34;show&#34;);
    }
});
    </script>
    <script>
      document.addEventListener(&#34;DOMContentLoaded&#34;, function () {

  /* -----------------------------
   * Helpers
   * ----------------------------- */
  function csrf(){
    const el = document.querySelector(&#39;meta[name=&#34;csrf-token&#34;]&#39;);
    return el ? el.content : &#39;&#39;;
  }

  const ua = navigator.userAgent.toLowerCase();
  if (/(bot|crawler|spider|headless|python|curl)/i.test(ua)) return;

  function uid(prefix){
    return prefix + &#34;_&#34; + Math.random().toString(36).substr(2,16);
  }

  function deviceHash(){
    let v = localStorage.getItem(&#39;device_hash&#39;);
    if (v) return v;

    v = uid(&#39;device&#39;);
    localStorage.setItem(&#39;device_hash&#39;, v);
    document.cookie = &#34;device_hash=&#34; + v + &#34;;path=/;max-age=31536000;SameSite=Lax&#34;;
    return v;
  }

  function sessionToken(){
    let v = sessionStorage.getItem(&#39;webnet_session_token&#39;);
    if (v) return v;

    v = uid(&#39;sess&#39;);
    sessionStorage.setItem(&#39;webnet_session_token&#39;, v);
    document.cookie = &#34;session_token=&#34; + v + &#34;;path=/;max-age=1800;SameSite=Lax&#34;;
    return v;
  }

  const dh = deviceHash();
  const st = sessionToken();

  /* -----------------------------
   * DWELL TRACKING STATE
   * ----------------------------- */
  let pageStart = Date.now();
  let lastUrl   = location.href;

  /* -----------------------------
   * Send helpers
   * ----------------------------- */
  function send(event, extra = {}){
    fetch(&#34;https://perstarke-webdev.de/track-visit&#34;, {
      method: &#34;POST&#34;,
      headers: {
        &#39;X-CSRF-TOKEN&#39;: csrf(),
        &#39;Content-Type&#39;: &#39;application/json&#39;
      },
      body: JSON.stringify(Object.assign({
        current_url: location.href,
        referer: document.referrer || null,
        user_agent: navigator.userAgent,
        session_token: st,
        device_hash: dh,
        event: event
      }, extra))
    }).catch(() =&gt; {});
  }

  function ping(){
    fetch(&#34;https://perstarke-webdev.de/track-ping&#34;, {
      method: &#34;POST&#34;,
      headers: {
        &#39;X-CSRF-TOKEN&#39;: csrf(),
        &#39;Content-Type&#39;: &#39;application/json&#39;
      },
      body: JSON.stringify({
        session_token: st
      })
    }).catch(() =&gt; {});
  }

  /* -----------------------------
   * DWELL SENDER
   * ----------------------------- */
  function sendDwell(){
    const seconds = Math.round((Date.now() - pageStart) / 1000);
    if (seconds &lt; 3) return; // ignore micro-bounces

    fetch(&#34;https://perstarke-webdev.de/track-visit&#34;, {
      method: &#34;POST&#34;,
      headers: {
        &#39;X-CSRF-TOKEN&#39;: csrf(),
        &#39;Content-Type&#39;: &#39;application/json&#39;
      },
      body: JSON.stringify({
        current_url: lastUrl,
        session_token: st,
        device_hash: dh,
        event: &#34;dwell&#34;,
        seconds: seconds
      })
    }).catch(() =&gt; {});
  }

  /* -----------------------------
   * INITIAL LOAD
   * ----------------------------- */
  send(&#39;page_load&#39;);
  ping();

  /* -----------------------------
   * CLICK TRACKING
   * ----------------------------- */
  document.addEventListener(&#34;click&#34;, function (e) {
    if (e.target.closest(&#34;a&#34;)) {
      send(&#34;click&#34;);
    }
  });

  /* -----------------------------
   * SCROLL TRACKING
   * ----------------------------- */
  let lastScrollY = scrollY;
  window.addEventListener(&#34;scroll&#34;, function () {
    if (Math.abs(scrollY - lastScrollY) &gt; 200) {
      lastScrollY = scrollY;
      send(&#34;scroll&#34;);
    }
  });

  /* -----------------------------
   * VISIBILITY / UNLOAD (DWELL)
   * ----------------------------- */
  document.addEventListener(&#34;visibilitychange&#34;, function () {
    if (document.visibilityState === &#34;hidden&#34;) {
      sendDwell();
    }
  });

  window.addEventListener(&#34;beforeunload&#34;, function () {
    sendDwell();
  });

  /* -----------------------------
   * HEARTBEAT
   * ----------------------------- */
  setInterval(function () {
    if (document.visibilityState === &#34;visible&#34;) {
      send(&#34;heartbeat&#34;);
      ping();
    }
  }, 60000);

  setInterval(ping, 20000);

});
    </script>
    <script>
      document.addEventListener(&#34;DOMContentLoaded&#34;, function () {
    if (!localStorage.getItem(&#34;cookieAccepted&#34;)) {
      document.getElementById(&#34;cookieBanner&#34;).style.display = &#34;block&#34;;
    }

    document.getElementById(&#34;acceptCookies&#34;).addEventListener(&#34;click&#34;, function () {
      localStorage.setItem(&#34;cookieAccepted&#34;, &#34;true&#34;);
      document.getElementById(&#34;cookieBanner&#34;).style.display = &#34;none&#34;;
    });
  });
    </script>
    <!--<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js" integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>-->
  </body>
</html>
