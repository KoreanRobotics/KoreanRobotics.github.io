---
layout: common
permalink: /
categories: projects
---

<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>Korean-American Robotics Association (KARA)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="멘토링, 세미나, 연구 교류, 산업 네트워킹을 위한 한미 로보틱스 커뮤니티" />

  <!-- Open Graph -->
  <meta property="og:title" content="Korean-American Robotics Association (KARA)" />
  <meta property="og:description" content="Mentoring · Seminars · Research Exchange · Industry Connections" />
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
  <script src="./src/popup.js" type="text/javascript" defer></script>

  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-5LDYQBVKHZ"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){ dataLayer.push(arguments); }
    gtag('js', new Date());
    gtag('config', 'G-5LDYQBVKHZ');
  </script>

  <style>
    :root {
      --kara-green: #186814;       /* keep as accent (links, highlights) */
      --kara-text: #2b2b2b;        /* main dark text (good contrast on #edf4f7) */
      --kara-muted: #5c6670;       /* slightly cooler gray to match the blue tone */
      --kara-bg-strip: #edf4f7;    /* section header background */
      --container-max: 1000px;
    }
    html { scroll-behavior: smooth; }
    body { font-family: "Open Sans", sans-serif; font-weight: 300; font-size: 18px; margin: 0; color: var(--kara-text); line-height: 1.6; }
    h1, h2, h3 { font-family: "Didact Gothic", sans-serif; font-weight: 700; margin: 0 0 10px; color: #000; }
    h1 { font-size: 2.2rem; }
    h2 { font-size: 1.8rem; position: relative; padding-left: 0.25rem; }
    h3 { font-size: 1.2rem; font-weight: 600; }
    /* 다양한 불릿 옵션 */
    /* 옵션1: 삼각형 */
    .bullet-triangle::before { content: "▸"; }
    /* 옵션2: 동그라미 */
    .bullet-circle::before { content: "●"; }
    /* 옵션3: 네모 */
    .bullet-square::before { content: "■"; }
    /* 기본 스타일 */
    h2::before { content: none; color: var(--kara-green); font-size: 1.1rem; position: absolute; left: -20px; top: 0.15em; }
    a { color: var(--kara-green); text-decoration: none; font-weight: 600; }
    a:hover, a:focus { text-decoration: underline; outline: none; }
    .container { max-width: var(--container-max); margin: 0 auto; padding: 0 16px; }
    .section-container { position: relative; width: 100%; }
    .section-background { position: absolute; inset: 0; width: 100%; z-index: 0; pointer-events: none; background-color: var(--kara-bg-strip); }
    .section-content { position: relative; z-index: 1; }
    .spacer { height: 20px; }
    .spacer-sm { height: 10px; }
    .spacer-lg { height: 40px; }
    .hero h1 strong { font-weight: 800; }
    .subhead { color: var(--kara-muted); margin-top: 6px; }
    .nav { display: flex; gap: 24px; flex-wrap: wrap; justify-content: center; font-size: 0.98rem; }
    .nav a { color: var(--kara-muted); }
    .seminar-list { list-style: none; padding: 0; margin: 0; }
    .seminar-item { display: grid; grid-template-columns: 140px 1fr; gap: 12px; padding: 14px 0; border-bottom: 1px solid #eee; }
    .seminar-item:last-child { border-bottom: none; }
    .seminar-date { font-weight: 700; color: #111; }
    .seminar-title { font-weight: 600; }
    .seminar-presenters { color: #555; }
    .organizers-grid { display: grid; grid-template-columns: repeat(5, 1fr); gap: 20px; }
    .organizer { text-align: center; }
    .profile { width: 100px; height: 100px; border-radius: 50%; object-fit: cover; display: block; margin: 0 auto 8px; }
    .muted { color: #666; font-size: 0.95rem; }
    .social-icons { display: flex; justify-content: center; gap: 12px; margin-top: 6px; }
    .social-icons a i { font-size: 1.3rem; color: var(--kara-green); transition: color 0.2s; }
    .social-icons a:hover i { color: #0a66c2; }
    .center { text-align: center; }
    .see-more { margin-top: 10px; font-size: 0.95rem; }
    /* Contact 제목은 불릿 제거 */
    #contact h2::before { content: none; }
  </style>
</head>

<body>
  <div class="section-container">
    <div class="section-background"></div>
    <div class="section-content">
      <div class="container">
        <div class="spacer"></div>

        <header class="hero">
          <h1><strong>Korean-American Robotics Association (KARA)</strong></h1>
          <h3 class="subhead">멘토링 · 세미나 · 연구 교류 · 산업 네트워킹</h3>
          <h3 class="subhead">Founded in 2025 · Online &amp; In-person</h3>
        </header>

        <div class="spacer"></div>

        <nav class="nav" aria-label="Section navigation">
          <a href="#mission">Mission & Activities</a>
          <a href="#seminars">Seminars</a>
          <a href="#organizers">Organizers</a>
        </nav>

        <div class="spacer"></div>
      </div>
    </div>
  </div>

  <main class="container">
    <div class="spacer-sm"></div>
    <section id="quicklinks">
      <h2>Quick Links</h2>
      <ul>
        <li><i class="fa-solid fa-video"></i> <a href="https://utexas.zoom.us/j/97343134961?pwd=yc8JkUJ4uT7ArNF7LOG8UrkCcOfOGs.1" target="_blank">세미나 Zoom 링크</a></li>
        <li><i class="fa-solid fa-calendar-days"></i> <a href="https://shorturl.at/Z11KU" target="_blank">Google Calendar</a></li>
        <li><i class="fa-brands fa-linkedin"></i> <a href="https://www.linkedin.com/groups/13352540/" target="_blank">LinkedIn</a></li>
        <li><i class="fa-brands fa-slack"></i> <a href="https://shorturl.at/dS4QC" target="_blank">Slack</a></li>
        <li><i class="fa-solid fa-envelope"></i> <a href="https://shorturl.at/w3S21" target="_blank">Mailing List 가입</a></li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <section id="mission">
      <h2>Mission & Activities</h2>
      <p><strong>Korean-American Robotics Association (KARA)</strong>는 로보틱스 분야의 한인 및 한미 학생, 연구자, 산업 종사자 커뮤니티이며, 아래와 같은 활동은 진행중입니다.</p>
      <ul>
        <li>멘토링 — 학생과 연구자, 산업 전문가를 연결</li>
        <li>세미나 & 워크숍 — 최신 연구 및 노하우 공유</li>
        <li>연구 교류 — 진행 중인 연구 발표와 협업</li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <section id="seminars">
      <h2>Seminars (Recent 4)</h2>
      <ul class="seminar-list">
        <li class="seminar-item"><div class="seminar-date">2025-10-16</div><div><div class="seminar-title">Sensorimotor Abstraction for Learning Generalizable Skills across Diverse Robots</div><div class="seminar-presenters">Presenter: Mingyo Seo (Ph.D. Student, UT Austin)</div></div></li>
        <li class="seminar-item"><div class="seminar-date">2025-10-02</div><div><div class="seminar-title">Socially and Contextually Aware Navigation for Robots in Human-Centric Environments</div><div class="seminar-presenters">Presenter: Daeun Song (Postdoctoral Researcher, George Mason)</div></div></li>
        <li class="seminar-item"><div class="seminar-date">2025-09-18</div><div><div class="seminar-title">Cotrol Contraction Metric-Guided Reinforcement Learning for Robust Path Tracking</div><div class="seminar-presenters">Presenter: Minjae Choi (Ph.D Student, UIUC)</div></div></li>
        <li class="seminar-item"><div class="seminar-date">2025-09-04</div><div><div class="seminar-title">Open Discussion: Vision-Language-Action Models</div><div class="seminar-presenters">Presenter: Dongho Kang (Ph.D Student, UT Austin)</div></div></li>
      </ul>
    </section>

    <div class="spacer-lg"></div>

    <section id="organizers">
      <h2 id="organizers-heading">Organizers</h2>
      <div class="organizers-grid">
        <div class="organizer"><img class="profile" src="./src/figure/organizers/mseo.png" alt="Mingyo Seo" /><p><span>Mingyo Seo</span><br><span class="muted">Ph.D. Student<br>UT Austin</span></p></div>
        <div class="organizer"><img class="profile" src="./src/figure/organizers/skim.png" alt="Sungmin Kim" /><p><span>Sungmin Kim</span><br><span class="muted">Ph.D. Student<br>Georgia Tech</span></p></div>
        <div class="organizer"><img class="profile" src="./src/figure/organizers/dkang.jpg" alt="Dongho Kang" /><p><span>Dongho Kang</span><br><span class="muted">Ph.D. Student<br>UT Austin</span></p></div>
        <div class="organizer"><img class="profile" src="./src/figure/organizers/ysung.png" alt="Yoonchang Sung" /><p><span>Yoonchang Sung</span><br><span class="muted">Assistant Professor<br>NTU/UT Austin</span></p></div>
        <div class="organizer"><img class="profile" src="./src/figure/organizers/wjung.png" alt="Wonsuhk Jung" /><p><span>Wonsuhk Jung</span><br><span class="muted">Ph.D. Student<br>Georgia Tech</span></p></div>
        <div class="organizer"><img class="profile" src="./src/figure/organizers/slee.png" alt="Seongwon Lee" /><p><span>Seongwon Lee</span><br><span class="muted">Ph.D. Student<br>UIUC</span></p></div>
      </div>
    </section>

    <div class="spacer-lg"></div>

  </main>

  <footer class="section-container">
    <div class="section-background" style="background-color:#edf4f7;"></div>
    <div class="section-content">
      <div class="container center">
        <p class="muted">© <span id="year"></span> Korean-American Robotics Association · All rights reserved.</p>
      </div>
    </div>
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
