---
layout: page
title: Mike Condon
---

## About Me

![Bio Photo](/pictures/bio_photo.jpg){: width="200px" style="float: right; margin-left: 20px;"}

I'm Mike Condon, welcome to my personal site. Here, you can find reports for my projects where I bridge between statistics, applied math, neuroscience and psychology. 
I am currently studying an MSc at the University of Nottingham and I'm looking for research opportunities. If you are interested, please send me an email at [{{ site.email }}](mailto:{{ site.email }}).


## Projects

<div class="project">
  <h3><a href="https://github.com/mikecondon/project-1">Maze Exploration with Context Trees</a></h3>
  <div class="project-meta">2025 | Bayesian Statistics, Markov Chains, Python</div>
  <p>When mice explore a tunnel system, which branch do they take? I use Bayesian Context Trees to uncover their pattern of decisions.</p>
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
