---
layout: common
permalink: /
categories: projects
---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Korean-American Robotics Association</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Mentoring, seminars, research exchange, and industry connections for Korean-American robotics students and professionals." />

  <!-- Open Graph -->
  <meta property="og:title" content="Korean-American Robotics Association" />
  <meta property="og:description" content="Mentoring, seminars, research exchange, and industry connections for Korean-American robotics students and professionals." />
  <meta property="og:image" content="./src/figure/kara_logo.png" />
  <meta property="og:image:width" content="880" />
  <meta property="og:image:height" content="220" />
  <meta property="og:url" content="https://koreanamericanrobotics.org/" />

  <!-- Fonts & Icons -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Didact+Gothic&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <!-- Your CSS -->
  <link media="all" href="./css/glab.css" type="text/css" rel="stylesheet" />

  <!-- Optional: your popup logic (kept) -->
  <script src="./src/popup.js" type="text/javascript" defer></script>

  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-5LDYQBVKHZ"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){ dataLayer.push(arguments); }
    gtag('js', new Date());
    gtag('config', 'G-5LDYQBVKHZ');
  </script>

  <!-- Page helpers -->
  <script>
    // Match background strip height to content block height
    window.addEventListener("DOMContentLoaded", function () {
      const sections = document.querySelectorAll('.section-container');
      sections.forEach(section => {
        const background = section.querySelector('.section-background');
        const content = section.querySelector('.section-content');
        if (background && content) background.style.height = content.offsetHeight + "px";
      });
    });

    // Smooth scroll for anchor links (fallback for older browsers)
    document.addEventListener("click", function (e) {
      const link = e.target.closest('a[href^="#"]');
      if (!link) return;
      const target = document.querySelector(link.getAttribute('href'));
      if (!target) return;
      e.preventDefault();
      target.scrollIntoView({ behavior: "smooth", block: "start" });
    });
  </script>

  <!-- Styles -->
  <style>
    :root {
      --kara-green: #186814;
      --kara-text: #2b2b2b;
      --kara-muted: #484824;
      --kara-bg-strip: #ebffe7;
      --container-max: 1000px;
    }

    html { scroll-behavior: smooth; }
    body {
      font-family: "Open Sans", sans-serif;
      font-weight: 300;
      font-size: 18px;
      margin: 0;
      color: var(--kara-text);
      line-height: 1.6;
    }

    h1, h2, h3 {
      font-family: "Didact Gothic", sans-serif;
      font-weight: 700;
      margin: 0 0 10px;
      color: #000;
    }

    h1 { font-size: 2.2rem; }
    h2 { font-size: 1.8rem; }
    h3 { font-size: 1.2rem; font-weight: 600; }

    a {
      color: var(--kara-green);
      text-decoration: none;
      font-weight: 600;
    }
    a:hover, a:focus { text-decoration: underline; outline: none; }

    /* Layout */
    .container {
      max-width: var(--container-max);
      margin: 0 auto;
      padding: 0 16px;
    }

    .section-container {
      position: relative;
      width: 100%;
    }
    .section-background {
      position: absolute;
      inset: 0;
      width: 100%;
      z-index: 0;
      pointer-events: none;
      background-color: var(--kara-bg-strip);
    }
    .section-content {
      position: relative;
      z-index: 1;
    }

    /* Hero / Header */
    .spacer { height: 20px; }
    .spacer-lg { height: 40px; }

    .hero h1 strong { font-weight: 800; }
    .subhead { color: var(--kara-muted); margin-top: 6px; }

    /* Simple navbar */
    .nav {
      display: flex;
      gap: 24px;
      flex-wrap: wrap;
      justify-content: center;
      font-size: 0.98rem;
    }
    .nav a { color: var(--kara-muted); }

    /* Content blocks */
    .card-list { margin: 12px 0; padding: 0; list-style: none; }
    .card {
      border: 1px solid #e5e5e5;
      border-radius: 10px;
      padding: 16px;
      margin: 12px 0;
      background: #fff;
    }

    /* Previous seminar list */
    .seminar-list { list-style: none; padding: 0; margin: 0; }
    .seminar-item {
      display: grid;
      grid-template-columns: 140px 1fr;
      gap: 12px;
      padding: 14px 0;
      border-bottom: 1px solid #eee;
    }
    .seminar-item:last-child { border-bottom: none; }
    .seminar-date { font-weight: 700; color: #111; }
    .seminar-title { font-weight: 600; }
    .seminar-presenters { color: #555; }

    /* Organizers */
    .organizers-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 20px;
    }
    .organizer {
      text-align: center;
    }
    .profile {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      margin: 0 auto 8px;
    }
    .muted { color: #666; font-size: 0.95rem; }

    /* Social icons */
    .social-icons {
      display: flex;
      justify-content: center;
      gap: 12px;
      margin-top: 6px;
    }
    .social-icons a i {
      font-size: 1.3rem;
      color: var(--kara-green);
      transition: color 0.2s;
    }
    .social-icons a:hover i {
      color: #0a66c2; /* LinkedIn blue hover */
    }

    /* Tables (kept minimal) */
    table { border-collapse: collapse; width: 100%; }

    /* Mobile tweaks */
    @media (max-width: 900px) {
      .organizers-grid { grid-template-columns: repeat(3, 1fr); }
    }
    @media (max-width: 600px) {
      .organizers-grid { grid-template-columns: repeat(2, 1fr); }
      .seminar-item { grid-template-columns: 1fr; }
    }

    /* Utility */
    .pill {
      display: inline-block;
      padding: 4px 10px;
      border-radius: 999px;
      background: #f2f7f2;
      border: 1px solid #dfe8df;
      font-size: 0.9rem;
      color: var(--kara-green);
      margin-right: 6px;
    }
    .highlight { color: var(--kara-green); font-weight: 600; }
    .center { text-align: center; }
  </style>
</head>

<body>
  <!-- Top band with soft green background -->
  <div class="section-container">
    <div class="section-background"></div>
    <div class="section-content">
      <div class="container">
        <div class="spacer"></div>

        <!-- HERO -->
        <header class="hero">
          <h1><strong>Korean-American Robotics Association</strong></h1>
          <h3 class="subhead">Mentoring • Seminars • Research Exchange • Industry Connections</h3>
          <h3 class="subhead">Founded in 2025 · Online &amp; In-person</h3>
        </header>

        <div class="spacer"></div>

        <!-- NAV -->
        <nav class="nav" aria-label="Section navigation">
          <a href="#mission">Our Mission</a>
          <a href="#activities">Activities</a>
          <a href="#upcoming">Upcoming Events</a>
          <a href="#previous">Previous Events</a>
          <a href="#organizers">Organizers</a>
          <a href="#contact">Contact</a>
        </nav>

        <div class="spacer"></div>
      </div>
    </div>
  </div>

  <!-- MAIN CONTENT -->
  <main class="container">
    <div class="spacer"></div>

    <!-- Mission -->
    <section id="mission" aria-labelledby="mission-heading">
      <h2 id="mission-heading">Our Mission</h2>
      <p>
        The <strong>Korean-American Robotics Association (KARA)</strong> is a community of Korean and Korean-American students, researchers, and professionals in robotics. Our mission is to:
      </p>
      <ul>
        <li>Mentorship — Connecting students with experienced researchers and industry experts.</li>
        <li>Seminars &amp; Workshops — Sharing cutting-edge research and practical know-how.</li>
        <li>Research Exchange — Presenting ongoing work and fostering collaboration.</li>
        <li>Industry Engagement — Bridging academia and industry to accelerate innovation.</li>
      </ul>
      <p>KARA supports members’ growth, collaboration, and visibility in the global robotics community.</p>
    </section>

    <div class="spacer-lg"></div>

    <!-- Activities -->
    <section id="activities" aria-labelledby="activities-heading">
      <h2 id="activities-heading">Activities</h2>
      <p>
        We plan biweekly research seminars, mentorship, and industry spotlights.
        Join our mailing list via the <a href="#contact">Contact</a> section.
      </p>
      <ul>
        <li>Research Presentations — Member talks with Q&amp;A and paper discussions.</li>
        <li>Seminars &amp; Workshops — Invited speakers and hands-on tutorials.</li>
        <li>Industry Connections — Career panels and networking sessions.</li>
        <li>Mentorship Program — Mentor matching and application guidance.</li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <!-- Upcoming -->
    <section id="upcoming" aria-labelledby="upcoming-heading">
      <h2 id="upcoming-heading">Upcoming Seminar</h2>
      <ul class="seminar-list" aria-live="polite">
        <li class="seminar-item">
          <div class="seminar-date">Aug 21, 2025</div>
          <div>
            <div class="seminar-title">Fast Ground-to-Air Transition Enabled by Avian-Inspired Multifunctional Legs</div>
            <div class="seminar-presenters">Presenter: Won Dong Shin (Assistant Professor, POSTECH)</div>
          </div>
        </li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <!-- Previous -->
    <section id="previous" aria-labelledby="previous-heading">
      <h2 id="previous-heading">Previous Seminars</h2>

      <ul class="seminar-list" aria-live="polite">
        <li class="seminar-item">
          <div class="seminar-date">Aug 21, 2025</div>
          <div>
            <div class="seminar-title">Fast Ground-to-Air Transition Enabled by Avian-Inspired Multifunctional Legs</div>
            <div class="seminar-presenters">Presenter: Won Dong Shin (Assistant Professor, POSTECH)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">July 24, 2025</div>
          <div>
            <div class="seminar-title">Radiation Source Localization using Mobile Robot</div>
            <div class="seminar-presenters">Presenter: Hojoon Son (Ph.D. Student, Georgia Tech)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">July 10, 2025</div>
          <div>
            <div class="seminar-title">Toward Real-Time Open-Vocabulary Semantic Mapping for Outdoor Robot Navigation</div>
            <div class="seminar-presenters">Presenter: Seungchan Kim (Ph.D. Student, Carnegie Mellon)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">Jun 26, 2025</div>
          <div>
            <div class="seminar-title">Versatile Trajectory Planner for Aerial Tracking</div>
            <div class="seminar-presenters">Presenter: Yunwoo Lee (Postdoctoral Researcher, Carnegie Mellon)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">June 12, 2025</div>
          <div>
            <div class="seminar-title">Machine Learning-based Online Monitoring with Robots for Nuclear Power Plants</div>
            <div class="seminar-presenters">Presenter: Sungmin Kim (Ph.D. Student, Geogia Tech)</div>
          </div>
        </li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <!-- Organizers -->
    <section id="organizers" aria-labelledby="organizers-heading">
      <h2 id="organizers-heading">Organizers</h2>
      <div class="organizers-grid" role="list">
        <!-- Mingyo Seo -->
        <div class="organizer" role="listitem">
          <img class="profile" src="./src/figure/organizers/jkim.jpg" alt="Portrait of Mingyo Seo" />
          <p>
            <span>Mingyo Seo</span><br>
            <span class="muted">Ph.D. Student<br>UT Austin</span>
          </p>
          <div class="social-icons">
            <a href="https://www.linkedin.com/in/mingyo/" aria-label="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://example.com/jkim" aria-label="Personal Website">
              <i class="fas fa-globe"></i>
            </a>
          </div>
        </div>

        <!-- Yoonchang Sung -->
        <div class="organizer" role="listitem">
          <img class="profile" src="./src/figure/organizers/sohn.jpg" alt="Portrait of Yoonchang Sung" />
          <p>
            <span>Yoonchang Sung</span><br>
            <span class="muted">Assistant Professor<br>NTU/UT Austin</span>
          </p>
          <div class="social-icons">
            <a href="https://www.linkedin.com/in/yoonchangsung/" aria-label="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://example.com/sohn" aria-label="Personal Website">
              <i class="fas fa-globe"></i>
            </a>
          </div>
        </div>

        <!-- Sungmin Kim -->
        <div class="organizer" role="listitem">
          <img class="profile" src="./src/figure/organizers/park.jpg" alt="Portrait of Sungmin Kim" />
          <p>
            <span>Sungmin Kim</span><br>
            <span class="muted">Ph.D. Student<br>Georgia Tech</span>
          </p>
          <div class="social-icons">
            <a href="https://www.linkedin.com/in/sungmin-me/" aria-label="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://example.com/park" aria-label="Personal Website">
              <i class="fas fa-globe"></i>
            </a>
          </div>
        </div>

        <!-- Wonsuhk Jung -->
        <div class="organizer" role="listitem">
          <img class="profile" src="./src/figure/organizers/choi.jpg" alt="Portrait of Wonsuhk Jung" />
          <p>
            <span>Wonsuhk Jung</span><br>
            <span class="muted">Ph.D. Student<br>Georgia Tech</span>
          </p>
          <div class="social-icons">
            <a href="https://www.linkedin.com/in/wonsuhk-jung/" aria-label="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://wonsuhkjung.wordpress.com/" aria-label="Personal Website">
              <i class="fas fa-globe"></i>
            </a>
          </div>
        </div>

        <!-- Seongwon Lee -->
        <div class="organizer" role="listitem">
          <img class="profile" src="./src/figure/organizers/lee.jpg" alt="Portrait of Seongwon Lee" />
          <p>
            <span>Seongwon Lee</span><br>
            <span class="muted">Ph.D. Student<br>UIUC</span>
          </p>
          <div class="social-icons">
            <a href="https://www.linkedin.com/in/scott-seongwon-lee-789b05221/" aria-label="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="https://sl148.github.io/" aria-label="Personal Website">
              <i class="fas fa-globe"></i>
            </a>
          </div>
        </div>
      </div>
    </section>

    <div class="spacer-lg"></div>

    <!-- Contact -->
    <section id="contact" aria-labelledby="contact-heading" class="center">
      <h2 id="contact-heading">Contact</h2>
      <p>
        For inquiries, please email
        <a href="mailto:info@koreanamericanrobotics.org"><span class="highlight">info@koreanamericanrobotics.org</span></a>.
      </p>
    </section>

    <div class="spacer-lg"></div>
  </main>

  <!-- Footer -->
  <footer class="section-container" role="contentinfo" aria-label="Site footer">
    <div class="section-background" style="background-color:#f7fff4;"></div>
    <div class="section-content">
      <div class="container center">
        <div class="spacer"></div>
        <p class="muted">© <span id="year"></span> Korean-American Robotics Association · All rights reserved.</p>
        <div class="spacer"></div>
      </div>
    </div>
  </footer>

  <script>
    // Set current year in footer
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
