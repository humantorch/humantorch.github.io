# humantorch.github.io

[![Hugo](https://img.shields.io/badge/built%20with-hugo-blue)](https://gohugo.io/) [![Theme: PaperMod](https://img.shields.io/badge/theme-PaperMod-lightgrey)](https://github.com/adityatelange/hugo-PaperMod) [![MIT License](https://img.shields.io/github/license/humantorch/humantorch.github.io)](LICENSE) [![GitHub last commit](https://img.shields.io/github/last-commit/humantorch/humantorch.github.io?color=green)](https://github.com/humantorch/humantorch.github.io/commits/main)


**Personal website and blog for Scott Kosman, Engineering Manager and Leadership Writer.**

---

## 🌐 Live Site

[scottkosman.com](https://scottkosman.com)

---

## 🚀 Quick Start

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.147.6+)
- Git

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/humantorch/humantorch.github.io.git
   cd humantorch.github.io
   ```

1. Clone the Papermod submodule:
   ```bash
   git submodule update --init
   ```

2. Start the development server:
   ```bash
   hugo server -D
   ```

3. Open your browser and navigate to `http://localhost:1313`

---

## 🏗️ Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/) (v0.147.6+)
- **Theme**: [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- **Hosting**: GitHub Pages
- **Custom Domain**: scottkosman.com
- **Analytics**: Simple Analytics (privacy-focused)

---

## 📁 Project Structure

```
humantorch.github.io/
├── content/          # Blog posts and pages
│   └── post/
│       └── blog/     # Blog posts
├── layouts/          # Custom templates
│   └── partials/     # Custom partials
│       └── templates/ # Open Graph templates
├── static/           # Images, CSS, JS
├── themes/           # PaperMod theme
└── config.yaml       # Site configuration
```

---

## ✨ Features

- **Responsive Design**: Mobile-first approach
- **Dark/Light Mode**: Automatic theme switching
- **Blog Section**: "Thoughts" section with latest post display on homepage
- **Social Media Integration**: LinkedIn share images for blog posts
- **SEO Optimized**: Open Graph and Twitter Card support
- **Privacy-First Analytics**: Simple Analytics integration
- **Fast Loading**: Static site generation
- **Custom Domain**: Fully configured for scottkosman.com

---

## 🎨 Customization

### Adding Blog Posts

1. Create a new markdown file in `content/post/blog/`
2. Use the following front matter structure:

```yaml
---
title: "Your Post Title"
date: YYYY-MM-DD
draft: false
ShowToc: true
description: "Brief description of your post"
cover:
  image: "https://scottkosman.com/your-cover-image.png"
  alt: "Alt text for your cover image"
ogimage: "https://scottkosman.com/your-linkedin-share-image.png"
tags:
  - tag1
  - tag2
---
```

### LinkedIn Share Images

- Create 1200x630px images for optimal LinkedIn sharing
- Add the `ogimage` parameter to your post front matter
- Images are automatically used for Open Graph meta tags

### Custom Styling

- Main CSS: `assets/css/extended/mine.css`
- Custom templates: `layouts/partials/`
- Open Graph templates: `layouts/partials/templates/`

---

## 📊 Analytics

The site uses [Simple Analytics](https://simpleanalytics.com/) for privacy-focused analytics:

- No cookies or tracking scripts
- GDPR compliant
- Free tier: 1,000 page views/month
- Automatically enabled via `config.yaml`

To disable analytics, set `simpleAnalytics.enabled: false` in your config.

---

## 🚀 Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

### Manual Build

```bash
hugo --environment production
```

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod) by Aditya Telange
- [Hugo](https://gohugo.io/) static site generator
- [Simple Analytics](https://simpleanalytics.com/) for privacy-focused analytics

---

*Domain registration not included in "free" hosting. Scott has owned this domain since 2003.*