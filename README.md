# VoidOps Technical Blog

Technical insights and project updates from VoidOps

## Overview

This is the GitHub Pages repository for VoidOps technical blog, built with Jekyll. The site is served at [blog.voidops.space](https://blog.voidops.space).

## Tutorial

### Local Development

To run the blog locally with Jekyll:

```bash
# Install Jekyll (if not already installed)
gem install bundler jekyll

# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

### Creating a New Post

Create a new file in the `_posts` directory with the format: `YYYY-MM-DD-title.md`

Example: `_posts/2025-01-06-welcome-to-voidops-blog.md`

```markdown
---
layout: post
title: "Welcome to VoidOps Blog"
date: 2025-01-06 10:00:00 +0900
author: VoidOps Team
tags: [announcement, introduction]
---

Your post content here...
```

### Building

To build the static site:

```bash
bundle exec jekyll build
```

The generated files will be in the `_site` directory.

