---
layout: layouts/main.njk
title: Home
hero:
  title: 'YongDo-Hyun'
  description: 'Software Developer & Open Source Enthusiast. Passionate about creating tools that empower users.'
  image:
    light: '/img/profile.jpg'
    dark: '/img/profile.jpg'
  button:
    url: /about
    content: 'Learn More'
---

<div class="home-sections">
  <section class="section about-section">
    <div class="section-heading">
      <h2>Welcome</h2>
      <p>Hi, I'm YongDo-Hyun, a developer focused on open-source software and user freedom. I work on projects that make technology more accessible and enjoyable.</p>
    </div>
  </section>

  <section class="section projects-section">
    <div class="section-heading">
      <p class="eyebrow">My Work</p>
      <h2>Featured Projects</h2>
    </div>
    <div class="projects-grid">
      <article class="project-card">
        <h3>ProjT Launcher</h3>
        <p>An open-source Minecraft launcher for managing multiple instances, mods, and more.</p>
        <a href="https://github.com/Project-Tick/ProjT-Launcher" target="_blank">View on GitHub</a>
      </article>
      <!-- Add more projects as needed -->
    </div>
  </section>

  <section class="section blog-section">
    <div class="section-heading">
      <p class="eyebrow">Latest Posts</p>
      <h2>From the Blog</h2>
    </div>
    {% include "postslist.njk" %}
  </section>

  <section class="section contact-section">
    <div class="section-heading">
      <h2>Get in Touch</h2>
      <p>Feel free to reach out for collaborations or just to say hello.</p>
      <a class="button" href="mailto:froster12@naver.com">Contact Me</a>
    </div>
  </section>
</div>
