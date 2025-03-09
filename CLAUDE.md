# Jekyll GitHub Pages Commands and Guidelines

## Development Commands
- Install dependencies: `bundle install`
- Start local server: `bundle exec jekyll serve`
- Build site: `bundle exec jekyll build`

## Project Structure
- Posts go in `_posts/` directory
- Use file naming format: `YYYY-MM-DD-title.markdown`
- Front matter required at top of content files (---)
- Images should be placed in `/assets/` 

## Style Guidelines
- Use Markdown for content formatting
- Code snippets should use {% highlight language %} blocks
- Follow Jekyll front matter conventions
- Maintain consistent spacing in YAML files

## Post Front Matter Format
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS +TIMEZONE
categories: category1 category2
---
```

## Theme
- Using minima theme (2.5)
- Customize via _config.yml