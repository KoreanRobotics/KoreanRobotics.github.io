---
layout: common
title: Past Seminars
permalink: /past-seminars/
categories: projects

seminars:
  - date: "2026-08-27"
    title: "Design of High-Power Underactuated Monopedal Hopping Robots"
    presenters: "Presenter: Gihyeok Na (PhD Student, University of Illinois at Urbana-Champaign)"
  - date: "2026-04-30"
    title: "Shaping Dexterity Through Hardware: Contact Morphology, Compliance, and Mechanism Design"
    presenters: "Presenter: Dong Ho Kang (PhD Student, University of Texas at Austin)"
    abstract:
      - >-
        Robotic manipulation is often framed as a problem of planning, perception, or control. However, the physical design of the robot itself fundamentally shapes what kinds of manipulation are possible, robust, and learnable. The core question focuses on how hardware design can be used as an active ingredient in manipulation, rather than a passive platform for algorithms.
      - >-
        The talk will center around the development of the PLATO Hand, a robotic hand designed to explore how fingertip morphology, compliance distribution, and mechanically structured contact surfaces affect grasping and in-hand interaction. Instead of maximizing degrees of freedom alone, PLATO investigates how anatomical features such as a compliant pulp, internal skeletal support, and nail-like reinforcement can improve contact stability, force transmission, and object interaction. These design choices are motivated by the idea that useful dexterity can emerge not only from actuation and control complexity, but also from carefully shaped contact mechanics.
  - date: "2026-04-16"
    title: "Scaling Multi-Robot Task and Motion Planning with Decomposable State Space Hypergraphs"
    presenters: "Presenter: Seongwon Lee (PhD Student, University of Illinois at Urbana-Champaign)"
    abstract:
      - >-
        As multi-robot systems scale, the search state space for Task and Motion Planning (TAMP) expands exponentially, causing traditional planners to suffer from a severe curse of dimensionality. This seminar introduces a strategy to tackle this large state space search problem by utilizing a decomposable, hypergraph-based framework that represents the search space concisely with linear growth and an efficient query process. To achieve this, the presentation introduces two complementary architectures: Lazy-DaSH, which improves the scalability of task and motion planning by employing hierarchical structures in hypergraph-based TAMP algorithms that delay expensive motion validation, and PDDL-DaSH, which extends hypergraph-based planning using symbolic task-level reasoning. This approach leverages the unique properties of hypergraphs to effectively resolve tightly coupled multi-robot interactions, scaling to significantly larger problems involving more robots and objects than state-of-the-art classical planners.
  - date: "2026-04-02"
    title: "Predictive Semantic Foresight for Mobile Robot Autonomy"
    presenters: "Presenter: Seungchan Kim (PhD Student, Carnegie Mellon University)"
    abstract:
      - >-
        Most autonomous mobile robots today remain trapped in the perceptual present: they reason only about what their sensors currently observe. While geometric mapping has enabled robots to represent their immediate surroundings and navigate within known space, these systems remain fundamentally reactive. I argue that robots must move beyond simple occupancy representations toward predictive semantic foresight: an internal model of what the world likely looks like and what it means. My research aims to endow autonomous mobile robots with the capacity to anticipate unobserved geometric and semantic information, and to leverage these representations for proactive, long-horizon decision-making. In this talk, I will present two complementary axes: (1) predictive mapping, which uses learned models to predict geometry beyond observed areas and enables probabilistic decision-making over these predictions; and (2) semantic reasoning, which embeds open-vocabulary, contextual understanding from vision-language foundation models into 3D representations to support open-world, goal-directed tasks. Looking ahead, I envision that a single unified predictive semantic representation can replace the patchwork of reactive perception modules that current robot systems rely on.
  - date: "2026-03-19"
    title: "Hardware, Control, and Learning for Aerial Manipulation"
    presenters: "Presenter: Dongjae Lee (Assistant Professor @ Kyung Hee University)"
    abstract:
      - >-
        Aerial manipulators have the potential to enable robotic physical interaction in environments that are difficult to access for ground robots, such as infrastructure inspection, maintenance, and disaster response. However, aerial manipulation remains challenging due to limited actuation authority, strong coupling between the aerial base and the manipulator, and disturbances induced by physical interaction.
      - >-
        In this talk, I will present our recent work on enabling reliable aerial manipulation through the integration of hardware design, robust/adaptive control, and policy learning. First, I introduce control frameworks for aerial physical interaction that ensure robust stability under unknown interaction forces and dynamic environments. Next, I present aerial platforms specifically designed for manipulation tasks, including tiltrotor-based systems that expand feasible interaction capabilities. Building on these developments, I will highlight our recent work on omnidirectional aerial manipulators that can perform manipulation at arbitrary poses in SE(3), enabled by geometric robust control and whole-body motion planning. Finally, I will discuss our recent efforts toward learning-based visuomotor policies that generalize manipulation behaviors for aerial robots.
  - date: "2026-03-05"
    title: "Open Discussion: Publishing in Robotics Journals and Conferences"
    presenters: "Presenter information not provided"
  - date: "2026-02-19"
    title: "Reinforcement learning referenced whole body MPPI for humanoid walking control"
    presenters: "Presenter: yunsoo seo (PhD Student @ UT Austin)"
    abstract:
      - >-
        Legged robots require unified control frameworks capable of generating dynamically consistent motions while maintaining robustness across hybrid contact phases. Conventional architectures based on a hierarchical separation between a simplified Center of Mass (CoM) planner and a full-order Whole-Body Controller (WBC) often suffer from model inconsistency, particularly during contact transitions and physically interactive tasks. This thesis aims to close this planner–controller gap by developing a unified whole-body predictive control framework based on Model Predictive Path Integral (MPPI) control.
      - >-
        The initial part of the work implements an analytical whole-body MPPI using the Rigid Body Dynamics Library (RBDL), where contact constraints are directly enforced through projection within the equations of motion. While this formulation produces dynamically consistent torque rollouts, it is limited by modeling inaccuracies and computational inflexibility during contact transitions.
      - >-
        To address these limitations, we introduce a simulation-driven MPPI within the MuJoCo MPC (MJPC) framework, where the physics engine resolves forward dynamics, contact events, and mode switches. Building on this environment, we propose an RL-referenced MPPI, in which a reinforcement learning (RL) policy supplies an adaptive mean prior that guides sampling. This integration improves sampling efficiency, robustness, and adaptability to out-of-distribution motions such as squatting and variable step lengths.
      - >-
        Across simulation experiments, the RL-referenced MPPI not only improves command-tracking accuracy on straight-line and speed-regulation tasks over a standalone RL walking policy, but also executes commands outside the RL training distribution, highlighting its robustness and adaptability beyond both purely analytical and purely simulation-based baselines. Taken together, these results advance a unified whole-body MPPI paradigm that integrates planning and control within a single predictive optimization framework, paving the way for more coherent and robust control of legged robots.
  - date: "2026-02-05"
    title: "Are you confident your sensor is tuned correctly? Robust Kalman filtering under noise uncertainty"
    presenters: "Presenter: Minhyuk Jang (PhD Student @ UIUC)"
    abstract:
      - >-
        State estimation is a core building block in robotics. It is the process of inferring a robot’s state (for example, position, velocity, and attitude) from sensor measurements such as IMU, odometry, GPS, vision, or radar. In practice, sensors are noisy and models are imperfect, so any state estimator must rely on noise statistics, which are parameters that describe process noise (how much we trust the dynamics) and sensor noise (how much we trust the measurements). Unfortunately, these parameters are rarely known accurately and are often chosen through manual tuning, heuristics, or limited experimental data. Even if you manage to tune your sensors so the system works properly, how confident are you that the tuning is actually correct?
      - >-
        In this talk, I will start with a motivating example that shows how incorrect noise parameters can degrade estimation performance and can lead to divergence and undesirable system behavior. Then, I will explain the intuition behind Kalman filtering and its nonlinear extension, the extended Kalman filter, focusing on how these noise parameters shape estimation behavior. Finally, I will present a robust Kalman filtering approach designed to remain reliable even when noise parameters are not perfectly tuned. Rather than assuming fixed and correct noise statistics, the method explicitly accounts for uncertainty in both process and sensor noise statistics and computes reliable noise models in a principled way, while preserving the standard filtering structure. I will also present experimental results on 3D target tracking using 3D radar measurements. The goal of this talk is to provide practical understanding and intuition about how poorly tuned state estimators can cause system failures, and how to address this issue in practice.
  - date: "2026-01-22"
    title: "Humanoid outdoor navigation: review, current progress, and future direction"
    presenters: "Presenter: Ziwon Yoon (Ph.D. Student @ Georgia Tech)"
    abstract:
      - >-
        Humanoids have advantages in maneuvering human-centered environments, but face greater failure risk compared to other stable mobile platforms, such as wheeled or quadrupedal robots. While learning-based traversability has been widely studied for these platforms, humanoids has instead relied on manually designed rules with limited consideration of bipedal stability on rough terrain. In this presentation, we review the existing traversability and navigation frameworks for mobile robots, and present the first learning-based traversability estimation and risksensitive navigation framework for bipedal humanoids operating in diverse, uneven environments.
  - date: "2025-12-11"
    title: "Failure-Resilient Grasping Through Inherent Functionality: Autonomous and Assistive Perspectives"
    presenters: "Presenter: Jungpyo Lee (Postdoc @ UC Berkeley)"
    abstract:
      - >-
        Robots remain brittle in unstructured environments where vision is unreliable and contact dynamics dominate. My research develops failure-resilient robotic systems by co-designing physical structure, sensing, and control to leverage inherent functionality that already exists within the system.
      - >-
        I will first introduce the Smart Suction Cup, a multi-chamber vacuum gripper that uses its internal pressure dynamics as natural tactile feedback. This enables haptic search, allowing robots to refine grasp alignment when visual perception breaks down, improving reliability by more than 2.5× and transferring to industrial tasks such as PCB manipulation.
      - >-
        I will then present the Dorsal Grasper, an assistive wearable device for individuals with cervical spinal cord injury. By harnessing the user’s inherent wrist extension to drive robotic finger flexion, the device achieves adaptive, shared grasp control without added sensors or complex computation, demonstrating reliable use across both lab and in-home environments.
      - >-
        Together, these systems show how robustness can emerge from design-centered intelligence, where physical embodiment and sensing dynamics work in tandem with control—providing a foundation for robots that truly operate in the real world.
  - date: "2025-11-13"
    title: "Discussion Session: Paths to Graduate Internship"
    presenters: "Presenters: Scott (Seongwon) Lee, Wonsuhk Jung, Mingyo Seo"
  - date: "2025-10-30"
    title: "Scaling Unsupervised Skill Discovery with Guidance"
    presenters: "Presenter: Seungeun (Ross) Rho (Ph.D. Student @ Georgia Tech)"
    abstract:
      - >-
        Unsupervised skill discovery aims to learn a diverse repertoire of behaviors through free interaction with the environment, without relying on any task-specific reward signals. While recent research has made notable progress, scaling these methods to high-degree-of-freedom agents or real-world systems remains highly challenging.
      - >-
        In this seminar, we will introduce three recent works addressing these challenges: (1) LGSD – leveraging large language models (LLMs) to inject semantic guidance during skill discovery, (2) SDAX – applying skill discovery to real-world legged robots, and (3) RGSD – guiding skill discovery using reference data to enable scalable learning for high-dimensional agents.
  - date: "2025-10-16"
    title: "Sensorimotor Abstraction for Learning Generalizable Skills across Diverse Robots"
    presenters: "Presenter: Mingyo Seo (Ph.D. Student @ UT Austin)"
  - date: "2025-10-02"
    title: "Socially and Contextually Aware Navigation for Robots in Human-Centric Environments"
    presenters: "Presenter: Daeun Song (Postdoc @ George Mason Univ.)"
    abstract:
      - >-
        Robots deployed in human-centric environments must navigate beyond geometric path planning, requiring awareness of context, social norms, and dynamic surroundings. They must navigate long distances without access to pre-built maps, while adapting to diverse terrains and environmental constraints that change over time. Also, the navigation further gets complicated by the need to respect human norms and respond to subtle, non-verbal cues such as gestures, posture, and head orientation. This talk presents recent advances that address these challenges. Together, these directions point toward navigation systems that are both robust to environmental complexity and sensitive to human presence, enabling robots to operate effectively in dynamic, real-world environments.
  - date: "2025-09-18"
    title: "Control Contraction Metric-Guided Reinforcement Learning for Robust Path Tracking"
    presenters: "Presenter: MJ (Minjae) Cho (PhD Student @ UIUC)"
    abstract:
      - >-
        Control contraction metrics (CCMs)—positive-definite Riemannian metrics under which a closed-loop system is guaranteed to be incrementally exponentially stable—can be used to synthesize a contracting policy in path-tracking problems. However, the synthesized policy only ensures pointwise satisfaction of the CCM conditions and does not consider long-term optimality (i.e., cumulative tracking error) over the entire trajectory. Furthermore, this myopic approach may make the policy more susceptible to learning biases when approximate dynamics are used to formulate CCMs. To address these issues, we propose to integrate CCMs into reinforcement learning (RL), where CCMs provide dynamics-informed feedback for learning a contracting policy while RL gives a framework for minimizing cumulative tracking error under approximate dynamics. We show that our algorithm, contraction actor-critic (CAC), enhances path-tracking performance and remains robust under approximation errors of dynamics compared to relevant baselines.
  - date: "2025-09-04"
    title: "Open Discussion: Vision-Language-Action Models"
    presenters: "Presenter information not provided"
  - date: "2025-08-21"
    title: "Fast Ground-to-Air Transition Enabled by Avian-Inspired Multifunctional Legs"
    presenters: "Presenter: Won Dong Shin (Assistant Professor at POSTECH)"
    abstract:
      - >-
        Most birds can navigate seamlessly between aerial and terrestrial environments. While their forelimbs have evolved into wings primarily for flight, their hindlimbs (legs) serve various functions such as walking, hopping, leaping, and jumping take-off for transitions into flight. Incorporating versatile legs into aerial vehicles could expand the range of robotic applications across diverse environments. In this seminar, RAVEN (Robotic Avian-inspired Vehicle for multiple ENvironments), capable of replicating the aforementioned bird-like abilities, will be introduced. Its design will be discussed, along with its performance in walking, hopping, jumping, and take-off, and insights from experimental results will be shared.
  - date: "2025-07-24"
    title: "Radiation Source Localization using Mobile Robot"
    presenters: "Presenter: Hojoon Son"
    abstract:
      - >-
        In this presentation, I outline a general approach to robotic radiation detection and its challenges. The material is based on the paper “Physics-Informed Radiation Multi-Source Localization with Robotic Platform.” An automated robotic platform with radiation detectors can aid in localizing radiation sources under various scenarios while preventing human exposure to ionizing radiation. This study proposes a novel robot-assisted radiation source localization process for multiple sources. The method is applicable in an environment with an unknown number of radiation sources and is capable of estimating source locations from sparse robot measurements while following a predefined path. A source-count classifier is trained with 59,911 high-fidelity 2D radiation flux simulation samples to derive the estimated number of radiation sources from the sparse measurements. Then, the derived number of sources, flux measurements, and measured locations are fed into physics-informed neural networks to localize multiple radiation sources precisely. The developed method outperforms other related research in terms of estimation error. Additionally, the method has been demonstrated with 3D radiation flux with different geometric configurations by case studies using Unreal Engine 5.
  - date: "2025-07-10"
    title: "Toward Real-Time Open-Vocabulary Semantic Mapping for Outdoor Robot Navigation"
    presenters: "Presenter: Seungchan Kim"
    abstract:
      - >-
        Open-vocabulary semantic mapping is crucial for robots to understand diverse semantic concepts about objects and scenes beyond fixed label sets, enabling more flexible and intelligent decision-making in downstream tasks such as navigation. In this talk, I will first provide an overview of recent trends in open-vocabulary semantic mapping, and then highlight several key challenges that arise in outdoor settings. Second, I will introduce RayFronts, an open-vocabulary semantic mapping system that captures semantics of far-range objects and achieves fine-grained vision-language alignment. Finally, I will discuss how this approach can be extended and adapted to enhance real-time robot navigation in complex outdoor environments.
  - date: "2025-06-26"
    title: "Versatile Trajectory Planner for Aerial Tracking"
    presenters: "Presenter: Yunwoo Lee"
    abstract:
      - >-
        This presentation introduces a trajectory planning framework for aerial target tracking, starting from a versatile single-agent tracker and extending to a distributed multi-agent system. The first part of the talk presents a sample-check-select pipeline that enables robust tracking in complex environments with dynamic obstacles and multiple targets. The second part extends this capability by introducing a distributed planning method based on Dynamic Buffered Voronoi Cells (DBVC) and Dynamic Inter-Visibility Cells (DIVC), allowing multiple aerial agents to cooperatively track targets while avoiding collisions and occlusions. Both approaches leverage Bernstein polynomial-based trajectory generation for real-time performance and are validated through extensive simulations and real-world experiments.
  - date: "2025-06-12"
    title: "Machine Learning-based Online Monitoring with Robots for Nuclear Power Plants"
    presenters: "Presenter: Sungmin Kim"
    abstract:
      - >-
        Online monitoring systems powered by sensors installed over the facilities have been an essential component in securing safety and efficiency in nuclear power plants (NPPs) for decades. However, due to limited information from a finite number of sensors, human workers are often required to be dispatched to the vicinity of the facilities for further inspections. To fully automate such processes with robots, this research presents a new machine learning based monitoring system with adaptive data acquisition from mobile robots. Along with the data constantly streamed from fixed sensors, the proposed system actively utilizes data from robots for improved diagnosis. The proposed framework includes: an initial robot deployment strategy with anomaly detection and localization method in a large scale NPPs, measurement selection algorithm based on constrained decision tree for faster and accurate diagnosis, and non-synchronous data compensation under transient conditions. The research also delineates key simulation techniques not only to improve dataset’s diversity, but also to evaluate the developed machine learning models in more quantitative ways.
  - date: "2025-05-29"
    title: "Open Discussion: ICRA Research Presentations"
    presenters: "Presenter information not provided"
  - date: "2025-05-15"
    title: "A Geometric Take on Motion Manifold Learning from Demonstration"
    presenters: "Presenter: Yonghyeon Lee"
    abstract:
      - >-
        One of the primary challenges in employing data-driven methods for generating robot movements is the high dimensionality of trajectories. This challenge is often further amplified by the small size of demonstration datasets. In this tutorial talk, we adopt the motion manifold hypothesis, which suggests that the high-dimensional trajectories approximately lie on a simpler, lower-dimensional space, referred to as the motion manifold. We then introduce a framework that leverages autoencoders to learn this motion manifold. This enables us to simultaneously learn the manifold and its coordinate chart, effectively addressing the issues of high dimensionality and small dataset sizes. Given this framework, several important questions naturally arise: (i) How can we deal with complex manifold structures, such as those with multiple connected components or holes; (ii) What constitutes good representations of trajectories; and (iii) How do we identify the most suitable latent coordinates for the manifold? Our tutorial will address these questions, providing both theoretical insights and practical strategies. Additionally, we will present experimental results from our research involving the 7-DoF Franka Panda robot arm, demonstrating the effectiveness of our approach in practical applications. This discussion is designed to offer a comprehensive overview of the challenges and solutions in learning the robot motion manifold from data, making it relevant for both researchers and practitioners in the field.
  - date: "2025-05-01"
    title: "Towards Adaptative Wheeled Humanoid Control: Leveraging Fast Parameter Estimation and Sim-to-Real Adaptation"
    presenters: "Presenter: Donghoon Baek"
    abstract:
      - >-
        Despite recent advances, robots still struggle to match human adaptability in interacting with complex environments. Humans benefit from intuitive understanding of physical surroundings—an ability robots lack. This motivates the question: What if we could quickly and accurately provide environmental information to robots? In this work, I propose a fast environmental physical parameter estimation framework using high-fidelity rigid body simulation with sim-to-real adaptation, integrated into an adaptive whole-body loco-manipulation controller for wheeled humanoid robots. Using our custom robot SATYRR and a human-machine interface, we developed a data-driven parameter estimator enhanced by system identification and Gaussian processes, followed by a hybrid sampling-based method that leverages vision-based 3D object size estimation, large language models, and parallel simulations to efficiently converge on inertial parameters. These estimates are incorporated into model-based and learning-based controllers to improve adaptability and performance, with hardware experiments.
  - date: "2025-04-17"
    title: "Open Discussion: Humanoid Research Discussion"
    presenters: "Presenter: Youngwoo Sim (PhD Student at UIUC)"
  - date: "2025-04-03"
    title: "Towards Scalable Robot Learning without Physical Robots"
    presenters: "Presenter: Younghyo Park (PhD Student at MIT)"
  - date: "2025-03-20"
    title: "Paper Review: Flow Matching and Its Applications in Robotics"
    presenters: "Presenter: Wonshuk Jung"
    abstract:
      - >-
        In this seminar, we provide an introductory review of the paper “Flow Matching for Generative Modeling” and explore its potential applications in robotics. We begin with an overview of generative modeling, outlining key model classes and their foundational principles. We then delve into the mathematical formulation of flow matching, discussing its theoretical underpinnings. Finally, we highlight recent advancements in applying flow matching techniques to robotics. This talk is intended for a broad audience, including those new to the topic, and will be structured similarly to a reading group discussion.
  - date: "2025-03-06"
    title: "Paper Review: Submodularity and Greedy Algorithms in Sensor Scheduling for Linear Dynamical Systems"
    presenters: "Presenter: Wooyeong Cho"
    abstract:
      - >-
        This paper focuses on sensor scheduling for state estimation, which consists of a network of noisy sensors and a discrete-time linear system with process noise. As an energy constraint, only a subset of sensors can take a measurement at each time step. These measurements are fused into a common state estimate using a Kalman filter and the goal is to schedule the sensors to minimize the estimation error at a terminal time. A simple approach is to greedily choose sensors at each time step to minimize the estimation error at the next time step. Recent work has shown that this greedy algorithm outperforms other well known approaches. Results have been established to show that the estimation error is a submodular function of the sensor schedule; submodular functions have a diminishing returns property that ensures the greedy algorithm yields near optimal performance. As a negative result, we show that most commonly-used estimation error metrics are not, in general, submodular functions. This disproves an established result. We then provide sufficient conditions on the system for which the estimation error is a submodular function of the sensor schedule, and thus the greedy algorithm yields performance guarantees.
  - date: "2025-02-20"
    title: "Design of Anthropomorphic Humanoid Robot for Whole Body Manipulation / Introduction to Task and Motion Planning"
    presenters: "Presenters: Dongho Kang, Seongwon Lee"
    abstract:
      - >-
        Design of Anthropomorphic Humanoid Robot for Whole Body Manipulation — Humanoid robots have significant potential due to their ability to operate within existing human-centered infrastructure. Their versatility in performing complex manipulation tasks is attributed to their multi-kinematic chains with highly redundant degrees of freedom (DoF). However, designing multi-DoF components such as the hand, hip, wrist, and ankle remains a considerable challenge, as current methodologies often rely on designers' intuition and experience rather than systematic optimization. My research aims to establish a framework for generating parameterized design choices that optimize whole-body manipulation tasks by considering critical factors such as gear ratios, transmission types, and joint configurations. By introducing key design choices and challenges in humanoid robot development, I present approaches for enhancing humanoid robot design and a dexterous robotic hand for versatile manipulation.
      - >-
        Introduction to Task and Motion Planning — Task and Motion Planning (TAMP) lies at the intersection of high-level task reasoning and low-level motion generation, playing a critical role in enabling autonomous systems to operate effectively in complex environments. This seminar will provide a comprehensive tutorial on the foundational concepts and modern approaches in TAMP. It will begin with an overview of integrated task and motion planning, followed by a discussion of motion planning fundamentals, including Configuration Space (C-space) as a key representation for robot motion. The seminar will then introduce two primary motion planning paradigms: sampling-based methods, such as Rapidly-exploring Random Trees (RRT) and Probabilistic Roadmaps (PRM), and optimization-based approaches, which formulate motion planning as a constrained optimization problem. The session will also cover the basics of task planning, introducing the Planning Domain Definition Language (PDDL) framework and commonly used planning techniques. The seminar will conclude with a discussion of open research questions and challenges in integrated task and motion planning. This session aims to provide both conceptual understanding and practical insights, serving as an accessible introduction to the field.
  - date: "2025-02-06"
    title: "Scalable Motor Skill Learning for Diverse Robot Embodiments / Extending Current Capabilities of Task and Motion Planning"
    presenters: "Presenters: Mingyo Seo, Yoonchang Sung"
---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Past Seminars | Korean-American Robotics Association</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Past seminars hosted by the Korean-American Robotics Association." />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Didact+Gothic&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" />
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
    .abstract-details { margin-top: 10px; }
    .abstract-details summary {
      display: inline-block;
      cursor: pointer;
      padding: 4px 10px;
      border: 1px solid #cbdcc8;
      border-radius: 999px;
      background: #f2f7f2;
      color: var(--kara-green);
      font-size: 0.9rem;
      font-weight: 600;
      list-style: none;
    }
    .abstract-details summary::-webkit-details-marker { display: none; }
    .abstract-details summary::before { content: "+"; margin-right: 6px; }
    .abstract-details[open] summary::before { content: "−"; }
    .abstract-details summary:focus-visible { outline: 2px solid var(--kara-green); outline-offset: 2px; }
    .abstract-content {
      margin-top: 10px;
      padding: 12px 14px;
      border-left: 3px solid #cbdcc8;
      background: #f8fbf8;
      color: #555;
      font-size: 0.95rem;
    }
    .abstract-content p { margin: 0 0 10px; }
    .abstract-content p:last-child { margin-bottom: 0; }
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
        {% for seminar in page.seminars %}
        <li class="seminar-item">
          <div class="seminar-date">{{ seminar.date }}</div>
          <div>
            <div class="seminar-title">{{ seminar.title | replace: " / ", "<br />" }}</div>
            <div class="seminar-presenters">{{ seminar.presenters }}</div>
            {% if seminar.abstract %}
            <details class="abstract-details">
              <summary>Abstract</summary>
              <div class="abstract-content">
                {% for paragraph in seminar.abstract %}
                <p>{{ paragraph }}</p>
                {% endfor %}
              </div>
            </details>
            {% endif %}
          </div>
        </li>
        {% endfor %}
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
