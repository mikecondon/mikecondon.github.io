---
layout: page
title: Mike Condon
---

## About Me

I'm a software engineer with a passion for building reliable, scalable systems. My background includes work in distributed systems, cloud architecture, and developer tooling. I believe in simple, pragmatic solutions to complex problems.

## Projects

<div class="project">
  <h3><a href="https://github.com/mikecondon/project-1">Project Name 1</a></h3>
  <div class="project-meta">2024 | Python, FastAPI</div>
  <p>A description of this project. What problem does it solve? What technologies does it use? What was your role in building it?</p>
</div>

<div class="project">
  <h3><a href="https://github.com/mikecondon/project-2">Project Name 2</a></h3>
  <div class="project-meta">2023 | TypeScript, React</div>
  <p>A description of this project. What problem does it solve? What technologies does it use? What was your role in building it?</p>
</div>

<div class="project">
  <h3><a href="https://github.com/mikecondon/project-3">Project Name 3</a></h3>
  <div class="project-meta">2022 | Rust, WebAssembly</div>
  <p>A description of this project. What problem does it solve? What technologies does it use? What was your role in building it?</p>
</div>

## Writing

I occasionally write about software engineering, systems design, and technical topics that interest me. You can find my latest posts below.

<ul class="post-list">
  {%- for post in site.posts limit:5 -%}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
      </a>
    </h3>
  </li>
  {%- endfor -%}
</ul>
