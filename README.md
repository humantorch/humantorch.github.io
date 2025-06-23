# humantorch.github.io

[![Hugo](https://img.shields.io/badge/built%20with-hugo-blue)](https://gohugo.io/) [![Theme: PaperMod](https://img.shields.io/badge/theme-PaperMod-lightgrey)](https://github.com/adityatelange/hugo-PaperMod)

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

---

## 📁 Project Structure

```
humantorch.github.io/
├── content/          # Blog posts and pages
│   └── post/
│       └── blog/     # Blog posts
├── layouts/          # Custom templates
├── static/           # Images, CSS, JS
├── themes/           # PaperMod theme
└── config.yaml       # Site configuration
```

---

## ✨ Features

- **Responsive Design**: Mobile-first approach
- **Dark/Light Mode**: Automatic theme switching
- **Blog Integration**: Latest post display on homepage
- **SEO Optimized**: Open Graph and Twitter Card support
- **Fast Loading**: Static site generation

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
tags:
  - tag1
  - tag2
---
```

### Custom Styling

- Main CSS: `assets/css/extended/mine.css`
- Custom templates: `layouts/partials/`

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

---

*Domain registration not included in "free" hosting. Scott has owned this domain since 2003.*