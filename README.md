<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">



  <!-- 
    - primary meta tags
  -->
  <title>ChriShots</title>
  <meta name="title" content="ChriShots">
  <meta name="description" content="This is a photographer portfolio html template, made by codewithsadee.">

  <!-- 
    - favicon
  -->
  <link rel="shortcut icon" href="./ChriShots.png" type="image/svg+xml">

  <!-- 
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!-- 
    - custom font link
  -->
  <link rel="stylesheet" href="./assets/font/font.css">

  <!-- 
    - preload images
  -->
  <link rel="preload" as="image" href="./assets/images/loading.png">
  <link rel="preload" as="image" href="./assets/images/loading-circle.svg">

</head>

<body class="active" id="top">

  <!-- 
    -#PRELOADING
  -->

  <div class="loading" data-loading>
    <img src="./assets/images/loading.png" width="100" height="100" alt="loading" class="img">
    <img src="./assets/images/loading-circle.svg" width="120" height="120" alt="" class="circle">
  </div>





  <!-- 
    - #HEADER
  -->

  <header class="header" data-header>
    <div class="container">

      <a href="https://www.facebook.com/ChriShotssss" class="logo">
        <img src="./assets/images/logo.png" width="150" height="150" alt="ChriShots">
      </a>

      <button class="nav-open-btn" aria-label="open menu" data-nav-toggler>
        <img src="./assets/images/menu.svg" width="17" height="17" alt="menu icon">
      </button>

      <nav class="navbar" data-navbar>

        <div class="navbar-top">
          <a href="https://www.facebook.com/ChriShotssss" class="logo">
            <img src="./assets/images/nav-logo.png" width="40" height="40" alt="Richard home" class="img">
          </a>

          <button class="nav-close-btn" aria-label="close menu" data-nav-toggler>
            <span class="span one"></span>
            <span class="span two"></span>
          </button>
        </div>

        <ul class="navbar-list">

          <li class="navbar-item">
            <a href="#home" class="navbar-link" data-nav-link>Home</a>
          </li>

          <li class="navbar-item">
            <a href="#gallery" class="navbar-link" data-nav-link>Gallery</a>
          </li>

          <li class="navbar-item">
            <a href="#about" class="navbar-link" data-nav-link>About</a>
          </li>

          <li class="navbar-item">
            <a href="#portfolio" class="navbar-link" data-nav-link>Portfolio</a>
          </li>

        </ul>

        <p class="navbar-title">My Address</p>

        <address class="navbar-text">
          623 Coral St. San Agustin, Iriga City, Camarines Sur / 4349 L. Bernardino St. Gen. T. De Leon, Valenzuela City
        </address>

        <p class="navbar-text">
          For Inquiry & Booking? Text/Call us at
          <a href="tel:09925996317" class="contact-link">+6399-2599-6317</a>
        </p>

      </nav>

      <div class="overlay" data-nav-toggler data-overlay></div>

    </div>
  </header>





  <main>
    <article>

      <!-- 
        - #HERO
      -->

      <section class="section hero" id="home" aria-label="home">
        <div class="container">

          <img src="./assets/images/hero-banner.png" width="322" height="322" alt="" class="hero-banner">

          <div class="hero-content">

            <h1 class="h1 hero-title">ChriShots</h1>

            <div class="wrapper h2">
              <strong class="strong" data-letter-effect>Photographer</strong>
              <strong class="strong" data-letter-effect>Film Maker</strong>
              <strong class="strong" data-letter-effect>Designer</strong>
              <strong class="strong" data-letter-effect>Traveler</strong>
            </div>

            <p class="hero-text">4 Years Of Experience</p>

          </div>

        </div>

        <img src="./assets/images/hero-shape.svg" width="211" height="189" alt="" class="shape">

      </section>





      <!-- 
        - #GALLERY
      -->

      <section class="section gallery" id="gallery">
        <div class="container">

          <ul class="gallery-list">

            <li class="gallery-item" data-reveal>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-1.jpg" width="450" height="625" loading="lazy" alt="Teaboom Cafe"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/photo/?fbid=310437031728285&set=pcb.310440911727897" class="card-title">Teaboom Cafe</a>
                  </h3>

                  <span class="card-tag">Food, Event Photography</span>
                </div>

                <a href="https://www.facebook.com/photo/?fbid=310437031728285&set=pcb.310440911727897" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-2.png" width="450" height="625" loading="lazy"
                    alt="Sunset" class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0tWeoP3wXMACLZpGNfZFfePD1HgHpGYKcgHCxitjsY9HqN5MJeB9tXJZT51zv7ZCKl" class="card-title">Sunset</a>
                  </h3>

                  <span class="card-tag">Landscape Photography</span>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0tWeoP3wXMACLZpGNfZFfePD1HgHpGYKcgHCxitjsY9HqN5MJeB9tXJZT51zv7ZCKl" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

            </li>

            <li class="gallery-item" data-reveal>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-3.jpg" width="450" height="625" loading="lazy" alt="C-Shake Model"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/photo?fbid=311541034951218&set=pcb.311541568284498" class="card-title">C-Shake Model</a>
                  </h3>

                  <span class="card-tag">Model, Fashion Photography</span>
                </div>

                <a href="https://www.facebook.com/photo?fbid=311541034951218&set=pcb.311541568284498" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-4.png" width="450" height="625" loading="lazy" alt="Couple Photowalk"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02rfWvpFHZ2cpzrgX79NJZZHuiuvtaUy7FduTCwcDyKezGvtvXRsS4f5ngF9tEFvDsl" class="card-title">Couple Photowalk</a>
                  </h3>

                  <span class="card-tag">Photowalk Photography</span>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02rfWvpFHZ2cpzrgX79NJZZHuiuvtaUy7FduTCwcDyKezGvtvXRsS4f5ngF9tEFvDsl" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

            </li>

            <li class="gallery-item" data-reveal>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-5.png" width="450" height="625" loading="lazy" alt="Jesus Is Lord Church Nabua 16th Anniversary Highlights"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/JILNabua/videos/1071186614152849" class="card-title">Jesus Is Lord Church Nabua 16th Anniversary Highlights</a>
                  </h3>

                  <span class="card-tag">Film Maker</span>
                </div>

                <a href="https://www.facebook.com/JILNabua/videos/1071186614152849" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-6.jpg" width="450" height="625" loading="lazy" alt="𝙼𝚛. & 𝙼𝚛𝚜 𝙹𝚞𝚍𝚊𝚟𝚊𝚛 Wedding"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/media/set/?set=a.194729393299050&type=3" class="card-title">𝙼𝚛. & 𝙼𝚛𝚜 𝙹𝚞𝚍𝚊𝚟𝚊𝚛 Wedding</a>
                  </h3>

                  <span class="card-tag">Wedding Photography</span>
                </div>

                <a href="https://www.facebook.com/media/set/?set=a.194729393299050&type=3" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

            </li>

            <li class="gallery-item" data-reveal>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-7.png" width="450" height="625" loading="lazy"
                    alt="Liberata 28's birthday Photoshoot" class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/media/set/?set=a.384777370960917&type=3" class="card-title">Liberata 28's birthday Photoshoot</a>
                  </h3>

                  <span class="card-tag">Birthday Photography</span>
                </div>

                <a href="https://www.facebook.com/media/set/?set=a.384777370960917&type=3" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

              <div class="gallery-card">

                <figure class="card-banner img-holder has-before" style="--width: 450; --height: 625;">
                  <img src="./assets/images/gallery-8.png" width="450" height="625" loading="lazy"
                    alt="Prinson Israel Dedication & 1st Birthday" class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h6">
                    <a href="https://www.facebook.com/media/set/?set=a.384902667615054&type=3" class="card-title">Prinson Israel Dedication & 1st Birthday</a>
                  </h3>

                  <span class="card-tag">Christening Photography</span>
                </div>

                <a href="https://www.facebook.com/media/set/?set=a.384902667615054&type=3" class="btn-icon">
                  <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy"
                    alt="arrow-forward icon">
                </a>

              </div>

            </li>

          </ul>

        </div>
      </section>





      <!-- 
        - #CATEGORY
      -->

      <section class="section category" aria-label="photography category">
        <div class="container">

          <ul class="category-list">

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid035zBGitPwQCXr4hWSA79panEmu4rihQN3hBb8GkmyyYuUw1cAkxHbxSyVnbp676sHl" class="category-card">

                <h3 class="h4 card-title">Landscape,</h3>

                <figure class="card-banner img-holder" style="--width: 800; --height: 690;">
                  <img src="./assets/images/category-1.png" width="800" height="690" loading="lazy" alt="Landscape"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02CaxgMhHGcJgpttCoTUFp3zVbWnQvi1U44Ld2MbZK4jxf2jw4TvJtdDLshWvYiB7al" class="category-card">

                <h3 class="h4 card-title">Model,</h3>

                <figure class="card-banner img-holder" style="--width: 600; --height: 690;">
                  <img src="./assets/images/category-2.png" width="600" height="690" loading="lazy" alt="Model"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/videos/1374678523409247/" class="category-card">

                <h3 class="h4 card-title">Food,</h3>

                <figure class="card-banner img-holder" style="--width: 800; --height: 690;">
                  <img src="./assets/images/category-3.png" width="800" height="690" loading="lazy" alt="Food"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/watch/?v=1071186614152849" class="category-card">

                <h3 class="h4 card-title">Film Maker,</h3>

                <figure class="card-banner img-holder" style="--width: 690; --height: 600;">
                  <img src="./assets/images/category-4.png" width="690" height="600" loading="lazy" alt="Film Maker"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/media/set/?set=a.380641424707845&type=3" class="category-card">

                <h3 class="h4 card-title">Birthday Photoshoot,</h3>

                <figure class="card-banner img-holder" style="--width: 600; --height: 690;">
                  <img src="./assets/images/category-5.png" width="600" height="690" loading="lazy" alt="Birthday Photoshoot"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0PTyeEhQ8KTn39PZjH2dpT9mkiqtxgzr6nuy7eQKweaYQwDmwTn7Yd2CPmXBXymp5l" class="category-card">

                <h3 class="h4 card-title">Event Photography,</h3>

                <figure class="card-banner img-holder" style="--width: 690; --height: 600;">
                  <img src="./assets/images/category-6.png" width="690" height="600" loading="lazy" alt="Event Photography"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/videos/323614077158964" class="category-card">

                <h3 class="h4 card-title">Wedding Photography,</h3>

                <figure class="card-banner img-holder" style="--width: 800; --height: 690;">
                  <img src="./assets/images/category-7.jpg" width="600" height="690" loading="lazy" alt="Wedding Photography"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="#" class="category-card">

                <h3 class="h4 card-title">Photowalk,</h3>

                <figure class="card-banner img-holder" style="--width: 800; --height: 690;">
                  <img src="./assets/images/category-8.png" width="800" height="690" loading="lazy" alt="Photowalk"
                    class="img-cover">
                </figure>

              </a>
            </li>

            <li class="category-item" data-reveal>
              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0NR3C4qtz8bEHpAbcnDG7WNFyvqhQoajmKwNDHAZBAEwyUw9UmhWz854nXFrey2NQl" class="category-card">

                <h3 class="h4 card-title">Christening Photography.</h3>

                <figure class="card-banner img-holder" style="--width: 600; --height: 690;">
                  <img src="./assets/images/category-9.jpg" width="600" height="690" loading="lazy" alt="Christening Photography"
                    class="img-cover">
                </figure>

              </a>
            </li>

          </ul>

        </div>
      </section>





      <!-- 
        - #ABOUT
      -->

      <section class="section about" id="about" aria-label="about me">
        <div class="container">

          <div class="about-content">

            <h2 class="h2 section-title" data-reveal="right">
              Hi. I’m <br>
              Chris
            </h2>

            <div class="wrapper has-before" data-reveal="right">

              <p class="section-text">
                A passionate
                <em class="em">photograher</em>
                who are Owner Of ChriShots and Working in this field for
                <em class="em">last 3 years.</em>
                I’m ready to give you my best.
              </p>

            </div>

          </div>

          <figure class="about-banner" data-reveal="left">

            <div class="img-holder has-before" style="--width: 512; --height: 684;">
              <img src="./assets/images/about-banner.jpeg" width="512" height="684" loading="lazy" alt="ChriShots"
                class="img-cover">
            </div>

            <img src="./assets/images/about-shape-2.svg" width="659" height="653" loading="lazy" alt=""
              class="shape shape-2">

          </figure>

          <img src="./assets/images/about-shape-3.svg" width="239" height="232" loading="lazy" alt=""
            class="shape shape-3">

        </div>
      </section>





      <!-- 
        - #SERVICE
      -->

      <section class="section service" id="service" aria-labelledby="service-lable">

        <p class="section-subtitle container" id="service-lable">My Services</p>

        <ul class="service-list">

          <li data-reveal>
            <div class="service-card container">

              <img src="./assets/images/service-1.jpg" width="340" height="380" loading="lazy" alt="Wedding Photography"
                class="img">

              <div>
                <h3 class="h3 card-title">Wedding Photography</h3>

                <p class="card-subtitle">
                  "Capturing Love's Eternal Moments."
                </p>
              </div>

              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0jkHBrsHjdTnhZQq7Ge1D4b9mUboTAwkxyXgtpVLnhKRt5VEZKY9ispjB5ErrSy7Ml" class="btn-icon" aria-label="See more">
                <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                  <path d="M0 10H41" stroke="white" stroke-width="2" />
                  <path d="M33 1L41.9 10.2727L33 19" stroke="white" stroke-width="2" />
                </svg>
              </a>

            </div>
          </li>

          <li data-reveal>
            <div class="service-card container">

              <img src="./assets/images/service-2.png" width="340" height="380" loading="lazy" alt="Christening Photography"
                class="img">

              <div>
                <h3 class="h3 card-title">Christening Photography</h3>

                <p class="card-subtitle">
                  "Sacred moments captured with love."
                </p>
              </div>

              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0ZhrwvoeYo7eCjvhVFccPT2qbyAwzanWhrKrk7HDxrRyqs1EegsFGhk7CPLh5EoNsl" class="btn-icon" aria-label="See more">
                <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                  <path d="M0 10H41" stroke="white" stroke-width="2" />
                  <path d="M33 1L41.9 10.2727L33 19" stroke="white" stroke-width="2" />
                </svg>
              </a>

            </div>
          </li>

          <li data-reveal>
            <div class="service-card container">

              <img src="./assets/images/service-3.png" width="340" height="380" loading="lazy" alt="Birthday Photography"
                class="img">

              <div>
                <h3 class="h3 card-title">Birthday Photography</h3>

                <p class="card-subtitle">
                  "Celebrating life's moments, beautifully captured."
                </p>
              </div>

              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0ezdgE6hUaqkUaKM8EuCbzfWgemZ3YXb3ukdRUKgRrkrGarcxLVbrwoQFYw1oMdePl" class="btn-icon" aria-label="See more">
                <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                  <path d="M0 10H41" stroke="white" stroke-width="2" />
                  <path d="M33 1L41.9 10.2727L33 19" stroke="white" stroke-width="2" />
                </svg>
              </a>

            </div>
          </li>

          <li data-reveal>
            <div class="service-card container">

              <img src="./assets/images/service-4.jpg" width="340" height="380" loading="lazy" alt="Event Photography"
                class="img">

              <div>
                <h3 class="h3 card-title">Event Photography</h3>

                <p class="card-subtitle">
                  "Capturing moments, framing memories beautifully."
                </p>
              </div>

              <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0873NkZupXASWCL17yA3cgkFDnuXpLwcbvACrLhMYFk8RWvedQyx11euTRTYSHfHgl" class="btn-icon" aria-label="See more">
                <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                  <path d="M0 10H41" stroke="white" stroke-width="2" />
                  <path d="M33 1L41.9 10.2727L33 19" stroke="white" stroke-width="2" />
                </svg>
              </a>

            </div>
          </li>

 <li data-reveal>
            <div class="service-card container">

              <img src="./assets/images/service-5.jpg" width="340" height="380" loading="lazy" alt="Film Maker"
                class="img">

              <div>
                <h3 class="h3 card-title">Film Maker</h3>

                <p class="card-subtitle">
                  "Cinematic storyteller capturing life's essence."
                </p>
              </div>

              <a href="https://www.facebook.com/ChriShotssss/videos/3328242897467286/" class="btn-icon" aria-label="See more">
                <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                  <path d="M0 10H41" stroke="white" stroke-width="2" />
                  <path d="M33 1L41.9 10.2727L33 19" stroke="white" stroke-width="2" />
                </svg>
              </a>

            </div>
          </li>

        </ul>

      </section>





      <!-- 
        - #PORTFOLIO
      -->

      <section class="section portfolio" id="portfolio" aria-labelledby="portfolio-label">
        <div class="container">

          <div class="portfolio-list">

            <div class="wrapper">

              <h2 class="h2 section-title" id="portfolio-label" data-reveal>My Recent Work.</h2>

              <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-1.jpg" width="850" height="700" loading="lazy" alt="Richard & Janicel Wedding Highlight"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/videos/1699666340938788" class="card-title">Richard & Janicel Wedding Highlight</a>
                  </h3>

                  <p class="card-tag">Film</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/videos/1699666340938788" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>

              <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-2.jpg" width="850" height="700" loading="lazy" alt="Karl & Sybel Wedding Highlights"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0iV9MwovUkaX4dGWywq9QiVN73MSGr85qZNZqdrDQf5foGB9h5KmcXpGVRS8cAwZfl" class="card-title">25th Silver Anniversary Grand Organizational Clan</a>
                  </h3>

                  <p class="card-tag">Event Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0iV9MwovUkaX4dGWywq9QiVN73MSGr85qZNZqdrDQf5foGB9h5KmcXpGVRS8cAwZfl" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>

              <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-3.jpg" width="850" height="700" loading="lazy" alt="Joanne's Pre-Debut Photoshoot"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02KgPdwsg2ugTJkoVLsfbUKDrncf7LRez5AZqCuWwSUv2jyoAkBc4B9QnZEqjgyv54l" class="card-title">Anj Portrait Photoshoot</a>
                  </h3>

                  <p class="card-tag">Portrait Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02KgPdwsg2ugTJkoVLsfbUKDrncf7LRez5AZqCuWwSUv2jyoAkBc4B9QnZEqjgyv54l" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>

            </div>

            <div class="wrapper">

              <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-4.jpg" width="850" height="700" loading="lazy" alt="John Danbert's Christening & 1st Birthday"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02TpWJNmkeQp86HjrjizRz8DvXtmzD3s6ctjwJhYzanq8PaRfbJy6q89KgdroxRSicl" class="card-title">Quennie & Mego Wedding</a>
                  </h3>

                  <p class="card-tag">Film, Wedding Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/videos/995437265707081" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>

              <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-5.jpg" width="850" height="700" loading="lazy" alt="Mr & Ms College Intramurals"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid023SnHQUMCWKafXKXU32Ei7cCDYFXCvrkJKQuTS6W9qwvu67Enc54fsLAaD9Taa5m4l" class="card-title">Mr & Ms College Intramurals</a>
                  </h3>

                  <p class="card-tag">Event Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid023SnHQUMCWKafXKXU32Ei7cCDYFXCvrkJKQuTS6W9qwvu67Enc54fsLAaD9Taa5m4l" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>
                            <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-6.jpg" width="850" height="700" loading="lazy" alt="Joanne's Pre-Debut Photoshoot"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0cSoHuejUYPMZ2Fkax46Wr91Y1iroBKzpDrvz5Lk1GtnTYQvhEhjrexGNCS8aUEpcl" class="card-title">San Agustin(Stand Alone)Senior High School 8th Gradution</a>
                  </h3>

                  <p class="card-tag">Event Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid0cSoHuejUYPMZ2Fkax46Wr91Y1iroBKzpDrvz5Lk1GtnTYQvhEhjrexGNCS8aUEpcl" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>

 <div class="portfolio-card" data-reveal>

                <figure class="card-banner img-holder has-before" style="--width: 850; --height: 700;">
                  <img src="./assets/images/portfolio-7.jpg" width="850" height="700" loading="lazy" alt="Binibining Sta Crus Sur 2025"
                    class="img-cover">
                </figure>

                <div class="card-content">
                  <h3 class="h4">
                    <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02q2kufpqpVWYpCZEwY7Y5fZCcMp5zgGy2GTfM7QqGhMscgSYuGX9xN1wa7bcf76Pfl" class="card-title">Binibining Sta Crus Sur 2025</a>
                  </h3>

                  <p class="card-tag">Event Photography</p>
                </div>

                <a href="https://www.facebook.com/ChriShotssss/posts/pfbid02q2kufpqpVWYpCZEwY7Y5fZCcMp5zgGy2GTfM7QqGhMscgSYuGX9xN1wa7bcf76Pfl" class="btn-icon" aria-label="See more">
                  <svg xmlns="http://www.w3.org/2000/svg" width="43" height="20" viewBox="0 0 43 20" fill="none">
                    <path d="M0 10H41" stroke="black" stroke-width="2" />
                    <path d="M33 1L41.9 10.2727L33 19" stroke="black" stroke-width="2" />
                  </svg>
                </a>

              </div>
            </div>

          </div>

          <img src="./assets/images/portfolio-shape.svg" width="286" height="232" loading="lazy" alt="" class="shape">

        </div>
      </section>

    </article>
  </main>





  <!-- 
    - #FOOTER
  -->

  <footer class="footer">

    <div class="footer-top section" id="contact">
      <div class="container">

        <p class="section-subtitle" data-reveal>Contact Us</p>

        <h2 class="h2 section-title" data-reveal>
          For inquiry, Booking? Send Message.
        </h2>

        <a href="https://www.facebook.com/ChriShotssss" class="btn-icon" data-reveal>
          <img src="./assets/images/arrow-forward.svg" width="43" height="20" loading="lazy" alt="arrow-forward icon">
        </a>

        <img src="./assets/images/footer-1.jpg" width="159" height="176" loading="lazy" alt="photography"
          class="abs-img abs-img-1" data-reveal>

        <img src="./assets/images/footer-2.jpg" width="265" height="275" loading="lazy" alt="photography"
          class="abs-img abs-img-2" data-reveal>

        <img src="./assets/images/footer-3.jpg" width="303" height="272" loading="lazy" alt="photography"
          class="abs-img abs-img-3" data-reveal>

        <img src="./assets/images/footer-4.jpg" width="175" height="175" loading="lazy" alt="photography"
          class="abs-img abs-img-4" data-reveal>

        <img src="./assets/images/footer-shape.svg" width="185" height="134" loading="lazy" alt="" class="shape">

      </div>
    </div>

    <div class="footer-bottom">
      <div class="container">

        <a href="#" class="logo">
          <img src="./assets/images/logo.png" width="150" height="150" loading="lazy" alt="ChriShots">
        </a>

        <ul class="social-list">

          <li>
            <a href="https://www.facebook.com/ChriShotssss" class="social-link">FB</a>
          </li>

          <li>
            <a href="https://www.instagram.com/chrishotss/" class="social-link">IG</a>
          </li>

        </ul>

        <p class="copyright">Capturing Life's Timeless Moments</p>

      </div>
    </div>

    <div class="footer-bg has-before">
      <img src="./assets/images/footer-bg.jpg" width="1920" height="1135" loading="lazy" alt="photography"
        class="img-cover">
    </div>

  </footer>





  <!-- 
    - #BACK TO TOP
  -->

  <a href="#top" class="back-top-btn" aria-label="back to top" data-back-top-btn>0%</a>





  <!-- 
    - #CUSTOM CURSOR
  -->

  <div class="cursor" data-cursor></div>





  <!-- 
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

</body>

</html>
