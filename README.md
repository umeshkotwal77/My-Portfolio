# My-Portfolio
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KOTWAL DEVZONE.COM</title>

  <!--- favicon-->
  <link href="assets/images/vplogo.png" rel="icon">

  <!-- <link rel="shortcut icon" href="./favicon.svg" type="image/svg+xml"> -->

  <!-- 
    - custom css link
  -->
  <link rel="stylesheet" href="style.css">

  <!-- 
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;700&family=Saira+Stencil+One&display=swap"
    rel="stylesheet">
</head>

<body id="top" class="dark_theme">

  <!-- 
    - #HEADER
  -->

  <header class="header" data-header>
    <div class="container">

      <h1 class="h1 logo">
        <a href="#">KOTWAL DEVZONE.COM<span>.</span></a>
      </h1>

      <div class="navbar-actions">

        <!-- <select name="language" id="lang">
          <option value="en">En</option>
        </select> --> 

        <button class="theme-btn" aria-label="Change Theme" title="Change Theme" data-theme-btn>
          <span class="icon"></span>
        </button>

      </div>
      
      <button class="nav-toggle-btn" aria-label="Toggle Menu" title="Toggle Menu" data-nav-toggle-btn>
        <span class="one"></span>
        <span class="two"></span>
        <span class="three"></span>
      </button>

      
      <nav class="navbar" data-navbar>
        <ul class="navbar-list">

          <li>
            <a href="#home" class="navbar-link">Home.</a>
          </li>

          <li>
            <a href="#about" class="navbar-link">About.</a>
          </li>

          <li>
            <a href="#skills" class="navbar-link">Skills.</a>
          </li>

          <li>
            <a href="#portfolio" class="navbar-link">Portfolio.</a>
          </li>

          <li>
            <a href="#contact" class="navbar-link">Contact.</a>
          </li>

        </ul>
        
      </nav>

    </div>
  </header>

  <main>
    <article class="container">

      <!-- 
        - #HERO
      -->

      <section class="hero" id="home">

        <figure class="hero-banner">

          <picture>
            <source srcset="./assets/images/main .png" media="(min-width: 768px)">
            <source srcset="./assets/images/main .png" media="(min-width: 500px)">
            <img src="./assets/images/main .png" alt="A man in a blue shirt with a happy expression"
              class="w-100">
          </picture>

        </figure>

        <div class="hero-content">

          <h2 class="h2 hero-title">We Design & Build Creative Website</h2>

          <a href="#contact" class="btn btn-primary">Get in touch</a>

        </div>

        &nbsp;
      

        <ul class="contac-social-list">

          <li>
            <a href="https://www.facebook.com/umesh.kotwal.9/" class="contact-social-link">
              <ion-icon name="logo-facebook"></ion-icon>

              <div class="tooltip">Facebook</div>
            </a>
          </li>

          <li>
            <a href="https://www.instagram.com/umeshkotwal_07/" class="contact-social-link">
              <ion-icon name="logo-instagram"></ion-icon>

              <div class="tooltip">Instagram</div>
            </a>
          </li>

          <li>
            <a href="https://www.linkedin.com/in/umesh-kotwal-187380254" class="contact-social-link">
              <ion-icon name="logo-linkedin"></ion-icon>

              <div class="tooltip">Linkedin</div>
            </a>
          </li>

          <li>
            <a href="https://github.com/umeshkotwal77" class="contact-social-link">
              <ion-icon name="logo-github"></ion-icon>

              <div class="tooltip">Github</div>
            </a>
          </li>

          <li>
            <a href="https://wa.me/916352001332" class="contact-social-link">
              <ion-icon name="logo-whatsapp"></ion-icon>

              <div class="tooltip">WhatsApp</div>
            </a>
          </li>

        </ul>

        <a href="#stats" class="scroll-down">Scroll</a>

      </section>

      <!-- 
        - #STATS
      -->

      <section class="stats" id="stats">
        <ul class="stats-list">

          <li>
            <a href="#about" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-1.png" alt="Badge icon">
              </div>

              <h2 class="h2 card-title">
                1 <strong>Years of Experience</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

          <li>
            <a href="#portfolio" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-2.png" alt="Checkmark icon">
              </div>

              <h2 class="h2 card-title">
                3+ <strong>Completed Projects</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

          <li>
            <a href="#" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-3.png" alt="Peoples rating icon">
              </div>

              <h2 class="h2 card-title">
                3+ <strong>Happy Clients</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

        </ul>
      </section>

      <!-- 
        - #ABOUT
      -->

      <section class="about" id="about">

        <figure class="about-banner">
          <img src="./assets/images/Group 4.png" alt="A man in a alice blue shirt with a thinking expression"
            class="w-100">
        </figure>

        <div class="about-content section-content">

          <p class="section-subtitle">About me</p>

          <h2 class="h3 section-title">Need  Creative Website ? I can Help You!</h2>

          <p class="section-text">
            I am a Frontend Developer based in SURAT, India. I am an Completed my graduation B.Tech In Computer Engineering from KCE College of Engineering, Jalgaon, Maharashtra . I am very passionate about 
            improving my coding skills & developing websites. I build Websites using HTML, CSS, JavaScript and JS Library ReactJs & Frontend Development.
             Working for myself to improve my skills. Love to build Frontend clones.
            <p class="section-text">
              Are you looking for a cool and professional website and unleash your online business? &nbsp;Don't worry we are here to provide
               you our best of services. Our services are Custom Website , Portfolio site , Company Profile , 
              Web Design and the main goal is to satisfy our client to the best services
            </p>
          </p>

          <div class="btn-group">
          <a href="#contact"> <button class="btn btn-secondary">Hire me</button> </a>

           <a href="assets/images/Umesh_CV.pdf"> <button class="btn btn-primary">Download cv</button></a>
          </div>

        </div>

      </section>


      <!-- 
        - #SKILLS & EDUCATION
      -->

      <section class="skills" id="skills">

        <div class="skills-content section-content">

          <p class="section-subtitle">My skills</p>

          <h2 class="h3 section-title">What My Programming Skills Included ?</h2>

          <p class="section-text">
            I Develop Simple, Intuitive and Responsive User Interface That helps Users Get Things Done With Less Effort
            and Time
            With Those Technologies.
          </p>

          <div class="skills-toggle" data-toggle-box>

            <button class="toggle-btn active" data-toggle-btn>Skills</button>
            <button class="toggle-btn" data-toggle-btn>Education</button>
          </div>

        </div>

        <div class="skills-box" data-skills-box>

          <ul class="skills-list">

            <li>
              <div class="skill-card">
                <div class="tooltip">HTML5</div>

                <div class="card-icon">
                  <img src="./assets/images/html5.png" alt="HTML5 logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">CSS3</div>

                <div class="card-icon">
                  <img src="./assets/images/css3.png" alt="CSS3 logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">JavaScript</div>

                <div class="card-icon">
                  <img src="./assets/images/javascript.png" alt="JavaScript logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Bootstrap</div>

                <div class="card-icon">
                  <img src="./assets/images/bootstrap.png" alt="Bootstrap logo">
                </div>
              </div>
            </li>


            <li>
              <div class="skill-card">
                <div class="tooltip">SASS</div>

                <div class="card-icon">
                  <img src="./assets/images/sass.png" alt="SASS logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">React Js</div>

                <div class="card-icon">
                  <img src="./assets/images/react.png" alt="React logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Github</div>

                <div class="card-icon">
                  <img src="./assets/images/git.png" alt="Git logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">VS Code</div>

                <div class="card-icon">
                  <img src="./assets/images/vs-code.png" alt="VS Code logo">
                </div>
              </div>
            </li>

          </ul>

          

          <ul class="tools-list">

            <li>
              <div class="skill-card">
                <div class="tooltip">MCA</div>

                <div class="card-icon">
                  <img src="./assets/images/mca.jpg" alt="MCA logo">
                </div>
              </div>
            </li>


            

            <li>
              <div class="skill-card">
                <div class="tooltip">12TH</div>

                <div class="card-icon">
                  <img src="./assets/images/12.png" alt="12 logo">
                </div>
              </div>
            </li>  

            <li>
              <div class="skill-card">
                <div class="tooltip">10TH</div>
                
                <div class="card-icon">
                  <img src="./assets/images/10th.png" alt="10th logo">
                </div>
              </div>
            </li>   

          </ul>

        </div>

      </section>


      


      <!-- 
        - #PROJECTS Start 
      -->


      <section class="project" id="portfolio">

        <ul class="project-list">

          <li>
            <div class="project-content section-content">

              <p class="section-subtitle">My Works</p>

              <h2 class="h3 section-title">See My Works Which Will Amaze You!</h2>

              <p class="section-text">
                We develop the best quality website that serves for the long-term. Well-documented, clean, easy and
                elegant interface
                helps any non-technical clients.
              </p>

            </div>
          </li>

          <li>
            <a href="https://kotwaldevzone.com" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-1.png" class="w-100" alt="A macintosh on a yellow background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">kotwaldevzone.com</h3>

                <time class="publish-date" datetime="2022-04">Mar 2024</time>
              </div>

            </a>
          </li>
          <li>
            <a href="# Will Come" class="project-card">
              <figure class="card-banner">
                <img src="./assets/images/project-2.png" class="w-100" alt="On a Blue background, a Wacom and a mouse.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">e-commerce.com(Coming Soon)</h3>

                <time class="publish-date" datetime="2022-04"> April 2024</time>
              </div>

            </a>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-3.png" class="w-100"
                  alt="A Cassette tape on a mellow apricot background.">
              </figure>
              <div class="card-content">
                <h3 class="h4 card-title">Coming Soon</h3>

                <time class="publish-date" datetime="2022-04">May 2024</time>
              </div>

            </a>
          </li>

          <!-- <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-4.png" class="w-100"
                  alt="Blue digital watch on a dark liver background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Lorem Ipsum Dolor 04</h3>

                <time class="publish-date" datetime="2022-04">April 2022</time>
              </div>

            </a>
          </li> -->

          <!-- <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-5.png" class="w-100"
                  alt="On a dark liver background, Airport luggage car carrying a luggage.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Lorem Ipsum Dolor 05</h3>

                <time class="publish-date" datetime="2022-04">April 2022</time>
              </div>

            </a>
          </li> -->

          <!-- <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-6.png" class="w-100"
                  alt="On a yellow background, a digital watch and a glass.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Lorem Ipsum Dolor 06</h3>

                <time class="publish-date" datetime="2022-04">April 2022</time>
              </div>

            </a>
          </li> -->


        </ul>

      </section>

        <!-- 
         # Project End
         -->



      


      <!-- 
        - #CONTACT START 
      -->

      <section class="contact" id="contact">

        <div class="contact-content section-content">

          <p class="section-subtitle">Contact</p>

          <h2 class="h3 section-title">Have You Any Project ? Please Drop a Message</h2>

          <p class="section-text">
            Get in touch and let me know how i can help. Fill out the form and i’ll be in touch as soon as possible.
          </p>

          <ul class="contact-list">

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="location-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Address:</h3>

                <address class="contact-info">
                 Surat , Gujarat , india 
                </address>
              </div>

            </li>

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="call-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Phone:</h3>

                <a href="tel:+91 6352001332" class="contact-info">+91 635-200-1332</a>
              </div>

            </li>

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="mail-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Email:</h3>
                <a href="mailto:umeshkotwal7@gmail.com" class="contact-info">umeshkotwal7@gmail.com</a>
                <a href="mailto:umeshkotwal07@gmail.com" class="contact-info">umeshkotwal07@gmail.com</a>
              </div>
            </li>

            <li>
              <ul class="contac-social-list">

                <li>
                  <a href="https://www.facebook.com/umesh.kotwal.9/" class="contact-social-link">
                    <div class="tooltip">Facebook</div>

                    <ion-icon name="logo-facebook"></ion-icon>
                  </a>
                </li>

                <li>
                  <a href="https://www.instagram.com/umeshkotwal_07/" class="contact-social-link">
                    <div class="tooltip">Instagram</div>

                    <ion-icon name="logo-instagram"></ion-icon>
                  </a>
                </li>

                <li>
                  <a href="https://www.linkedin.com/in/umesh-kotwal-187380254" class="contact-social-link">
                    <div class="tooltip">Linkedin</div>

                    <ion-icon name="logo-linkedin"></ion-icon>
                  </a>
                </li>

                <li>
                  <a href="https://github.com/umeshkotwal77" class="contact-social-link">
                    <div class="tooltip">Github</div>

                    <ion-icon name="logo-github"></ion-icon>
                  </a>
                </li>

              </ul>
            </li>

          </ul>

        </div>

        <form action="https://script.google.com/macros/s/AKfycbyqKyEDQwvDSqeHDq0QJIy_sYTizwt4hRT0pbUtmxEROBXNpptCG3zsRpEmrl_BZDg/exec"  method="POST" class="contact-form" name="contactform">
          <div class="form-wrapper">

            <label for="name" class="form-label">Name</label>

            <div class="input-wrapper">

              <input type="text" name="name" id="name" required placeholder="e.g Umesh Kotwal" class="input-field"  autocomplete="off">

              <ion-icon name="person-circle"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="email" class="form-label">Email</label>

            <div class="input-wrapper">

              <input type="email" name="email" id="email" required placeholder="e.g umeshkotwal7@gmail.com"
                class="input-field" autocomplete="off">

              <ion-icon name="mail"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="phone" class="form-label">Phone</label>

            <div class="input-wrapper">

              <input type="tel" name="phone" id="phone" required placeholder="Phone Number" class="input-field" autocomplete="off">

              <ion-icon name="call"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="message" class="form-label">Message</label>

            <div class="input-wrapper">

              <textarea name="message" id="message" required placeholder="Write message..."
                class="input-field" autocomplete="off"></textarea>

              <ion-icon name="chatbubbles"></ion-icon>

            </div>

          </div>

          <button type="submit" name="submit" class="btn btn-primary">Send</button>

        </form>

      </section>

    </article>
  </main>


  <!-- 
    -#CONTACT END
   -->


  <!-- 
    - #FOOTER START 
  -->

  <footer class="footer">
    <div class="container">

      <p class="h1 logo">
        <a href="#">
          KOTWALDEVZONE.COM<span>.</span>
        </a>
      </p>
      <p class="copyright">
        &copy; 2024 <a href="#">Umesh Kotwal</a>. All rights reserved
      </p>
    </div>
  </footer>


  <!-- 
    -#FOOTER END 
   -->


  <!-- 
    - #GO TO TOP
  -->

  <a href="#top" class="go-top" data-go-top title="Go to Top">
    <ion-icon name="arrow-up"></ion-icon>
  </a>



  <!-- 
    - custom js link
  -->
  <script src="script.js"></script>

  <!-- 
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
