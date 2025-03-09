---
layout: post
title:  "Building a Minimal Personal Website with Jekyll"
date:   2024-09-24 22:27:08 +0100
categories: jekyll web-development
---

As a software developer, having a personal website serves as both a portfolio and a space for technical writing. After considering various options, I settled on using Jekyll with GitHub Pages for its simplicity and focus on content.

## Why Jekyll?

Jekyll provides an excellent balance between customization and simplicity. Its static site generation means:

1. Fast loading times with minimal overhead
2. No database or server-side processing required
3. Simple deployment through GitHub Pages
4. Markdown-based content that's easy to write and maintain

{% highlight bash %}
# Starting a new Jekyll site is as simple as:
gem install jekyll bundler
jekyll new my-site
cd my-site
bundle exec jekyll serve
{% endhighlight %}

## Choosing a Minimal Design

For my personal site, I wanted something reminiscent of [gwern.net](https://gwern.net) - focusing on content with minimal distractions. To achieve this, I modified the default Minima theme with custom CSS that emphasizes:

1. Typography with comfortable line height and font size
2. Limited color palette (mostly blacks and blues)
3. Single-column layout that keeps content front and center
4. Clear section dividers that help organize information

## What's Next

This site will grow to include:
- Project documentation and case studies
- Technical writing on software engineering topics
- Experiments with web technologies
- Learning notes and research summaries

I invite you to check back as I continue to develop both the site and its content.

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/