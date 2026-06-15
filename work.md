---
layout: page
title: Work
---

<div class="page-title-header">
    <h1>Work</h1>
    <p>From neural interfaces to language models — building systems that reason about the world.</p>
</div>

<div class="work-chapter" id="google">
    <div class="chapter-header">
        <h2 class="chapter-org">Google</h2>
        <span class="chapter-period">2020 — Present</span>
    </div>

    <div class="work-entry" id="search-ai">
        <h3 class="work-entry-title">Search AI — Web Guide</h3>
        <p class="work-entry-role">Senior Software Engineer</p>
        <div class="work-entry-body">
            <p>Own the LLM-integration framework that powers <a href="https://blog.google/products-and-platforms/products/search/web-guide-labs/">Web Guide</a> — Google's AI-organized search results experience. The system uses a custom Gemini model with query fan-out to understand both search queries and web content, organizing results into thematic clusters that surface pages users would not otherwise discover.</p>
            <p>Responsible for the ranking heuristics and search experiences enabled by this framework, working at the intersection of large language models, multi-step reasoning, and knowledge representation.</p>
        </div>
    </div>

    <div class="work-entry" id="gemini">
        <h3 class="work-entry-title">Gemini</h3>
        <p class="work-entry-role">Software Engineer</p>
        <div class="work-entry-body">
            <p>Productionized multimodal models for serving, quantization, fine-tuning, and evaluation. Translated experimental model code into the production-grade infrastructure that shipped with the v1 launch of Gemini.</p>
            <p>Contributed to the <a href="https://arxiv.org/abs/2312.11805">Gemini technical report</a>, which has been cited over 2,500 times.</p>
        </div>
    </div>

    <div class="work-entry" id="tensorflow">
        <h3 class="work-entry-title">TensorFlow — tf.function</h3>
        <p class="work-entry-role">Software Engineer, Codebase Owner</p>
        <div class="work-entry-body">
            <p>Re-architected <code>tf.function</code> by introducing two new abstractions:</p>
            <ul>
                <li><strong>FunctionType</strong> — a comprehensive signature representation that controls type-checking, dispatch, and tracing. Designed as a formal type system for computation graphs, treating each function's signature the way type theory treats terms.</li>
                <li><strong>AtomicFunction</strong> — a minimal callable that bypasses Python overhead at the core of tf.function, speeding up Keras model training by 4%.</li>
            </ul>
            <p>Authored the public RFC for FunctionType and owned the tf.function codebase, providing design consultation and support to internal and external users.</p>
            <a class="work-entry-link" href="https://github.com/tensorflow/tensorflow/commits/master/?author=faizan-m">View commits on GitHub</a>
        </div>
    </div>
</div>

<div class="work-chapter" id="ctrl-labs">
    <div class="chapter-header">
        <h2 class="chapter-org">CTRL Labs</h2>
        <span class="chapter-period">2019</span>
    </div>

    <div class="work-entry">
        <h3 class="work-entry-title">Neural Interface for Robot Teleoperation</h3>
        <p class="work-entry-role">Research Intern</p>
        <div class="work-entry-body">
            <p>Mapped EMG-based readings of muscle activations to a hexapod robot's appendages, enabling fine-grained teleoperation through neuromuscular signals. Built an API in Go to parse neuromuscular information into concurrent motor commands for the robot's body parts.</p>
            <p>The work contributed to a USPTO patent on systems and methods for contextualized interactions with an environment. Featured in an NPR documentary on the technology.</p>
            <div class="work-entry-media">
                <div>{%- include extensions/youtube.html id='cdZLg4IORc0' -%}</div>
            </div>
        </div>
    </div>
</div>

<div class="work-chapter" id="tufts">
    <div class="chapter-header">
        <h2 class="chapter-org">Tufts University</h2>
        <span class="chapter-period">2016 — 2020</span>
    </div>

    <div class="work-entry" id="sail-on">
        <h3 class="work-entry-title">DARPA SAIL-ON — Novelty-Oriented AI Agent</h3>
        <p class="work-entry-role">Lead Developer, AIR Lab + HRI Lab</p>
        <div class="work-entry-body">
            <p>Designed a cognitive architecture integrating symbolic planning with reinforcement learning to build an AI agent that could recognize, express, and adapt to novel environmental changes in Polycraft (a Minecraft mod).</p>
            <ul>
                <li>Pioneered novelty detection capabilities — the agent could not only recognize environmental changes but express them symbolically for planning</li>
                <li>Achieved top performance in independent DARPA evaluations against competing approaches</li>
                <li>Led a group of graduate and undergraduate students to publish the system architecture</li>
            </ul>
            <p>Paper accepted at AAMAS 2021.</p>
        </div>
    </div>

    <div class="work-entry" id="ar-robot-visualization">
        <h3 class="work-entry-title">Visualizing a Robot's Perspective in Augmented Reality</h3>
        <p class="work-entry-role">Lead Researcher, AIR Lab</p>
        <div class="work-entry-body">
            <p>Built an AR system that renders a robot's internal state — perception, belief, and planning — as spatial visualizations overlaid on the physical world. The idea: if a robot's cognition is inherently spatial, the medium for communicating it should be too.</p>
            <ul>
                <li>Developed ROS nodes in C++ to transform, sample, and compress robot data in real time</li>
                <li>Built a Unity application supporting HoloLens, iPad, and Android</li>
                <li>Visualizations include LIDAR, costmaps, path planning, and localization particles</li>
            </ul>
            <p>Part of the Tufts team that won the <a href="https://venturebeat.com/2019/02/07/verizon-reveals-5g-education-tech-winners-hints-at-next-5g-cities/">Verizon 5G EdTech Challenge</a> and its $100K prize. Presented at HRI 2019 in South Korea.</p>
            <div class="work-entry-media">
                <div>{%- include extensions/youtube.html id='WjxJnggaNr8' -%}</div>
            </div>
        </div>
    </div>

    <div class="work-entry">
        <h3 class="work-entry-title">Robotics Club — Trinity College Fire Fighting Robot Contest</h3>
        <p class="work-entry-role">Team Lead</p>
        <div class="work-entry-body">
            <p>Led the development of the club's first ROS-enabled robot, capable of autonomous navigation in unknown environments using SLAM. Won the Olympiad in Senior Individual Category in 2018 and 2019.</p>
        </div>
    </div>

    <div class="work-entry">
        <h3 class="work-entry-title">International Mathematical Olympiad</h3>
        <p class="work-entry-role">Pakistani National Team, 2016</p>
        <div class="work-entry-body">
            <p>Selected for the Pakistani national team through an intensive mathematical problem-solving and analysis training program.</p>
        </div>
    </div>
</div>
