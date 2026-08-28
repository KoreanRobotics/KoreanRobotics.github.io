---
layout: common
title: Past Seminars
permalink: /past-seminars/
categories: projects
---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Past Seminars | Korean-American Robotics Association</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Past seminars hosted by the Korean-American Robotics Association." />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Didact+Gothic&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <style>
    :root {
      --kara-green: #186814;
      --kara-text: #2b2b2b;
      --kara-muted: #5c6670;
      --kara-bg-strip: #edf4f7;
      --container-max: 1000px;
    }
    html { scroll-behavior: smooth; }
    body { font-family: "Open Sans", sans-serif; font-weight: 300; font-size: 18px; margin: 0; color: var(--kara-text); line-height: 1.6; }
    h1, h2 { font-family: "Didact Gothic", sans-serif; font-weight: 700; margin: 0 0 10px; color: #000; }
    h1 { font-size: 2.2rem; }
    h2 { font-size: 1.8rem; }
    a { color: var(--kara-green); text-decoration: none; font-weight: 600; }
    a:hover, a:focus { text-decoration: underline; outline: none; }
    .container { max-width: var(--container-max); margin: 0 auto; padding: 0 16px; }
    .section-container { position: relative; width: 100%; }
    .section-background { position: absolute; inset: 0; width: 100%; z-index: 0; pointer-events: none; background-color: var(--kara-bg-strip); }
    .section-content { position: relative; z-index: 1; }
    .spacer { height: 20px; }
    .spacer-lg { height: 40px; }
    .hero { display: flex; align-items: baseline; justify-content: space-between; gap: 20px; flex-wrap: wrap; }
    .subhead { color: var(--kara-muted); margin: 0; font-size: 1rem; }
    .nav { display: flex; gap: 24px; flex-wrap: wrap; justify-content: center; font-size: 0.98rem; }
    .nav a { color: var(--kara-muted); }
    .seminar-list { list-style: none; padding: 0; margin: 0; }
    .seminar-item { display: grid; grid-template-columns: 140px 1fr; gap: 12px; padding: 14px 0; border-bottom: 1px solid #eee; }
    .seminar-item:last-child { border-bottom: none; }
    .seminar-date { font-weight: 700; color: #111; }
    .seminar-title { font-weight: 600; }
    .seminar-presenters { color: #555; }
    .back-link { margin: 0 0 24px; font-size: 0.95rem; }
    .muted { color: #666; font-size: 0.95rem; }
    .center { text-align: center; }
    @media (max-width: 600px) {
      .seminar-item { grid-template-columns: 1fr; gap: 2px; }
      .hero { display: block; }
      .subhead { margin-top: 4px; }
    }
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
          <p class="subhead">Past Seminars</p>
        </header>
        <div class="spacer"></div>
        <nav class="nav" aria-label="Page navigation">
          <a href="{{ '/' | relative_url }}">Home</a>
          <a href="{{ '/' | relative_url }}#seminars">Recent Seminars</a>
          <a href="https://tinyurl.com/4kv83ba7" target="_blank" rel="noopener">Zoom Link</a>
        </nav>
        <div class="spacer"></div>
      </div>
    </div>
  </div>

  <main class="container">
    <div class="spacer-lg"></div>
    <p class="back-link"><a href="{{ '/' | relative_url }}">← Back to KARA home</a></p>

    <section aria-labelledby="past-seminars-heading">
      <h2 id="past-seminars-heading">Past Seminars</h2>
      <p class="muted">A record of KARA seminars and discussion sessions, listed from newest to oldest.</p>

      <ul class="seminar-list">
        <li class="seminar-item">
          <div class="seminar-date">2026-08-27</div>
          <div>
            <div class="seminar-title">Design of High-Power Underactuated Monopedal Hopping Robots</div>
            <div class="seminar-presenters">Presenter: Gihyeok Na (PhD Student, University of Illinois at Urbana-Champaign)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-04-30</div>
          <div>
            <div class="seminar-title">Shaping Dexterity Through Hardware: Contact Morphology, Compliance, and Mechanism Design</div>
            <div class="seminar-presenters">Presenter: Dong Ho Kang (PhD Student, University of Texas at Austin)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-04-16</div>
          <div>
            <div class="seminar-title">Scaling Multi-Robot Task and Motion Planning with Decomposable State Space Hypergraphs</div>
            <div class="seminar-presenters">Presenter: Seongwon Lee (PhD Student, University of Illinois at Urbana-Champaign)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-04-02</div>
          <div>
            <div class="seminar-title">Predictive Semantic Foresight for Mobile Robot Autonomy</div>
            <div class="seminar-presenters">Presenter: Seungchan Kim (PhD Student, Carnegie Mellon University)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-03-19</div>
          <div>
            <div class="seminar-title">Hardware, Control, and Learning for Aerial Manipulation</div>
            <div class="seminar-presenters">Presenter: Dongjae Lee (Assistant Professor @ Kyung Hee University)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-03-05</div>
          <div>
            <div class="seminar-title">Open Discussion: Publishing in Robotics Journals and Conferences</div>
            <div class="seminar-presenters">Presenter information not provided</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-02-19</div>
          <div>
            <div class="seminar-title">Reinforcement learning referenced whole body MPPI for humanoid walking control</div>
            <div class="seminar-presenters">Presenter: yunsoo seo (PhD Student @ UT Austin)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-02-05</div>
          <div>
            <div class="seminar-title">Are you confident your sensor is tuned correctly? Robust Kalman filtering under noise uncertainty</div>
            <div class="seminar-presenters">Presenter: Minhyuk Jang (PhD Student @ UIUC)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2026-01-22</div>
          <div>
            <div class="seminar-title">Humanoid outdoor navigation: review, current progress, and future direction</div>
            <div class="seminar-presenters">Presenter: Ziwon Yoon (Ph.D. Student @ Georgia Tech)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-12-11</div>
          <div>
            <div class="seminar-title">Failure-Resilient Grasping Through Inherent Functionality: Autonomous and Assistive Perspectives</div>
            <div class="seminar-presenters">Presenter: Jungpyo Lee (Postdoc @ UC Berkeley)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-11-13</div>
          <div>
            <div class="seminar-title">Discussion Session: Paths to Graduate Internship</div>
            <div class="seminar-presenters">Presenters: Scott (Seongwon) Lee, Wonsuhk Jung, Mingyo Seo</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-10-30</div>
          <div>
            <div class="seminar-title">Scaling Unsupervised Skill Discovery with Guidance</div>
            <div class="seminar-presenters">Presenter: Seungeun (Ross) Rho (Ph.D. Student @ Georgia Tech)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-10-16</div>
          <div>
            <div class="seminar-title">Sensorimotor Abstraction for Learning Generalizable Skills across Diverse Robots</div>
            <div class="seminar-presenters">Presenter: Mingyo Seo (Ph.D. Student @ UT Austin)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-10-02</div>
          <div>
            <div class="seminar-title">Socially and Contextually Aware Navigation for Robots in Human-Centric Environments</div>
            <div class="seminar-presenters">Presenter: Daeun Song (Postdoc @ George Mason Univ.)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-09-18</div>
          <div>
            <div class="seminar-title">Control Contraction Metric-Guided Reinforcement Learning for Robust Path Tracking</div>
            <div class="seminar-presenters">Presenter: MJ (Minjae) Cho (PhD Student @ UIUC)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-09-04</div>
          <div>
            <div class="seminar-title">Open Discussion: Vision-Language-Action Papers</div>
            <div class="seminar-presenters">Presenter information not provided</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-08-21</div>
          <div>
            <div class="seminar-title">Fast Ground-to-Air Transition Enabled by Avian-Inspired Multifunctional Legs</div>
            <div class="seminar-presenters">Presenter: Won Dong Shin (Assistant Professor at POSTECH)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-07-24</div>
          <div>
            <div class="seminar-title">Radiation Source Localization using Mobile Robot</div>
            <div class="seminar-presenters">Presenter: Hojoon Son</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-07-10</div>
          <div>
            <div class="seminar-title">Toward Real-Time Open-Vocabulary Semantic Mapping for Outdoor Robot Navigation</div>
            <div class="seminar-presenters">Presenter: Seungchan Kim</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-06-26</div>
          <div>
            <div class="seminar-title">Versatile Trajectory Planner for Aerial Tracking</div>
            <div class="seminar-presenters">Presenter: Yunwoo Lee</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-06-12</div>
          <div>
            <div class="seminar-title">Machine Learning-based Online Monitoring with Robots for Nuclear Power Plants</div>
            <div class="seminar-presenters">Presenter: Sungmin Kim</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-05-29</div>
          <div>
            <div class="seminar-title">Open Discussion: ICRA Research Presentations</div>
            <div class="seminar-presenters">Presenter information not provided</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-05-15</div>
          <div>
            <div class="seminar-title">A Geometric Take on Motion Manifold Learning from Demonstration</div>
            <div class="seminar-presenters">Presenter: Yonghyeon Lee</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-05-01</div>
          <div>
            <div class="seminar-title">Towards Adaptative Wheeled Humanoid Control: Leveraging Fast Parameter Estimation and Sim-to-Real Adaptation</div>
            <div class="seminar-presenters">Presenter: Donghoon Baek</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-04-17</div>
          <div>
            <div class="seminar-title">Open Discussion: Humanoid Research Discussion</div>
            <div class="seminar-presenters">Presenter: Youngwoo Sim (PhD Student at UIUC)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-04-03</div>
          <div>
            <div class="seminar-title">Towards Scalable Robot Learning without Physical Robots</div>
            <div class="seminar-presenters">Presenter: Younghyo Park (PhD Student at MIT)</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-03-20</div>
          <div>
            <div class="seminar-title">Paper Review: Flow Matching and Its Applications in Robotics</div>
            <div class="seminar-presenters">Presenter: Wonshuk Jung</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-03-06</div>
          <div>
            <div class="seminar-title">Paper Review: Submodularity and Greedy Algorithms in Sensor Scheduling for Linear Dynamical Systems</div>
            <div class="seminar-presenters">Presenter: Wooyeong Cho</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">2025-02-20</div>
          <div>
            <div class="seminar-title">
              Design of Anthropomorphic Humanoid Robot for Whole Body Manipulation<br />
              Introduction to Task and Motion Planning
            </div>
            <div class="seminar-presenters">Presenters: Dongho Kang, Seongwon Lee</div>
          </div>
        </li>
        <li class="seminar-item">
          <div class="seminar-date">Date not specified</div>
          <div>
            <div class="seminar-title">
              Scalable Motor Skill Learning for Diverse Robot Embodiments<br />
              Extending Current Capabilities of Task and Motion Planning
            </div>
            <div class="seminar-presenters">Presenters: Mingyo Seo, Yoonchang Sung</div>
          </div>
        </li>
      </ul>
    </section>

    <div class="spacer-lg"></div>
  </main>

  <footer class="section-container">
    <div class="section-background"></div>
    <div class="section-content">
      <div class="container center">
        <div class="spacer"></div>
        <p class="muted">© <span id="year"></span> Korean-American Robotics Association · All rights reserved.</p>
        <div class="spacer"></div>
      </div>
    </div>
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
