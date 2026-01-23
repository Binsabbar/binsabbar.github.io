---
layout: default
title: Home
---

<div class="hero">
  <h1>Hi, I'm Mo 👋</h1>
  <p class="tagline">Go Developer & Cloud Native Enthusiast</p>
  <p class="subtitle">Building reliable, scalable systems // Solving complex infrastructure problems</p>

  <div class="skills">
    <span class="skill-tag">Go/Golang</span>
    <span class="skill-tag">Kubernetes</span>
    <span class="skill-tag">Cloud Native</span>
    <span class="skill-tag">DevOps</span>
    <span class="skill-tag">CI/CD</span>
    <span class="skill-tag">Docker</span>
    <span class="skill-tag">GitLab</span>
    <span class="skill-tag">CLI Tools</span>
  </div>
</div>

<div class="section">
  <h2>About Me</h2>

  <p>I'm a software engineer passionate about building robust, efficient systems using <strong>Go</strong> and <strong>Cloud Native technologies</strong>. I believe in the power of clean code, automation, and pragmatic solutions that solve real problems.</p>

  <h3>What I Do</h3>
  <ul>
    <li><strong>Go Development:</strong> Building high-performance applications, CLI tools, and microservices</li>
    <li><strong>Cloud Native Engineering:</strong> Kubernetes, containerization, and distributed systems</li>
    <li><strong>DevOps & Automation:</strong> CI/CD pipelines, infrastructure as code, monitoring solutions</li>
    <li><strong>Problem Solving:</strong> Turning complex challenges into simple, elegant solutions</li>
  </ul>

  <h3>My Approach</h3>
  <p>I focus on <strong>practical, production-ready solutions</strong> over over-engineering. Whether it's building a CLI tool to monitor 50+ GitLab pipelines or architecting cloud infrastructure, I prioritize:</p>
  <ul>
    <li>Simplicity and maintainability</li>
    <li>Real-world utility and performance</li>
    <li>Developer experience</li>
    <li>Open source collaboration</li>
  </ul>
</div>

<div class="section">
  <h2>How I Can Help You</h2>

  <p>Looking for expertise in Go or Cloud Native technologies? I'm here to help with:</p>

  <ul>
    <li><strong>Go Development:</strong> Architecture, code reviews, best practices, performance optimization</li>
    <li><strong>Kubernetes & Cloud:</strong> Cluster setup, deployment strategies, troubleshooting, scaling</li>
    <li><strong>CI/CD Pipelines:</strong> GitLab CI, automation, build optimization, monitoring</li>
    <li><strong>CLI Tool Development:</strong> Building developer tools that boost productivity</li>
    <li><strong>Mentoring:</strong> Helping teams adopt Go and Cloud Native practices</li>
  </ul>

  <p>I enjoy collaborating on open source projects and helping fellow engineers solve challenging problems. Feel free to reach out!</p>
</div>

<div class="section">
  <h2>Recent Articles</h2>

  <div class="blog-post">
    <p class="blog-date">24/09/2020</p>

    <h3>CLI Tool for monitoring Gitlab Pipelines</h3>

    <p><img src="https://raw.githubusercontent.com/Binsabbar/gitlab-cli-build-monitor/master/screenshot.png" alt="GitLab CLI Monitor Screenshot"></p>

    <p>During covid-19 and lockdown, I wanted to utilise my time with something interesting. During my day, I needed to track multiple projects build status for over 50 projects. It was hard and time consuming. Sometimes I forget to check, the other time I lose track and focus on my main task.</p>

    <p>So I wanted something simple that I can glimpse at. I was using Gitlab, and did not provide a Dashboard that displayed all pipeline status. So I created a simple cli tool that will monitor and check projects that I am interested in. It is the simplest and fastest thing I could make in such a limited time, while getting value out of it. Also, some people enjoy cli based tools more.</p>

    <p>The tool is not very sophisticated, but yet simple enough to use and get value out of it.</p>

    <p>The configuration is simple, all you need is a single <code>YAML</code> file that looks like that:</p>

    <pre><code>baseUrl: https://gitlab.com
accessToken: some-token-goes-here
projects: # list of either ID number or full path to project
- groupA/projectA
- userA/projectB
- groupA/projectB
- groupA/projectV
updateIntervals: 50 # in seconds</code></pre>

    <p>The above will monitor the lists of projects and displays the status of each of them.</p>

    <p>The project is still new and it has its own limitations such as: filtering branches or showing project that failed in the last X minutes. Feel free to contribute to it.</p>

    <p>You can find the repo <a href="https://github.com/Binsabbar/gitlab-cli-build-monitor">here</a> with more details.</p>
  </div>
</div>

<div class="cta">
  <h2>Let's Connect</h2>
  <p>Have a question about Go, Kubernetes, or Cloud Native tech? Need help with a project? Let's chat!</p>
  <a href="mailto:mo.opensource.projects@gmail.com" class="cta-button">Get in Touch</a>
  <a href="https://github.com/Binsabbar" class="cta-button">View GitHub</a>
</div>
