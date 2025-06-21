# humantorch.github.io

[![Hugo](https://img.shields.io/badge/built%20with-hugo-blue)](https://gohugo.io/) [![Theme: PaperMod](https://img.shields.io/badge/theme-PaperMod-lightgrey)](https://github.com/adityatelange/hugo-PaperMod)

**Personal website and blog for Scott Kosman, built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.**

---

## 🌐 Live Site

Visit: [https://scottkosman.com](https://scottkosman.com)  
(GitHub Pages: [https://humantorch.github.io](https://humantorch.github.io))

---

## 🚀 Project Overview

This site is a fast, modern, and minimal personal site and blog, deployed for free via GitHub Pages and mapped to a custom domain. It features:

- **About**: [About Scott](content/post/about.md) — background, philosophy, and story
- **Manager README**: [How To Scott](content/post/readme.md) — Scott's approach to management and working together
- **Journey**: [Career Journey](content/post/journey.md) — professional experience and highlights
- **Resume**: [PDF Resume](static/skosman_resume2023.pdf)
- **Contact & Social**: Linked in the profile section

---

## 🛠️ Tech Stack

- **[Hugo](https://gohugo.io/):** Static site generator
- **[PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod):** Clean, responsive, and highly customizable
- **GitHub Pages:** Free static hosting
- **Custom Domain:** [scottkosman.com](https://scottkosman.com)

---

## 📦 Quick Start

1. **Clone the repo:**
   ```bash
   git clone https://github.com/humantorch/humantorch.github.io.git
   cd humantorch.github.io
   git submodule update --init --recursive
   ```
2. **Install [Hugo](https://gohugo.io/getting-started/installing/):**
   - macOS: `brew install hugo`
   - Windows: [Download](https://github.com/gohugoio/hugo/releases)
3. **Run locally:**
   ```bash
   hugo server -D
   ```
   Visit [http://localhost:1313](http://localhost:1313)

---

## ⚙️ Configuration & Customization

- **Site config:** See [`config.yaml`](config.yaml) for site title, theme, menu, and profile settings.
- **Content:** All posts/pages are in [`content/post/`](content/post/).
- **Custom CSS:** Add styles in [`assets/css/extended/mine.css`](assets/css/extended/mine.css).
- **Profile & Socials:** Set in `config.yaml` under `params.profileMode` and `params.socialIcons`.
- **Theme updates:**
  - PaperMod is a git submodule in [`themes/PaperMod`](themes/PaperMod). Update with:
    ```bash
    git submodule update --remote --merge
    ```

---

## 🚢 Deployment

- **Automatic:** Pushing to `main` deploys to GitHub Pages.
- **Manual:** Build with `hugo` and push the `public/` folder to the `gh-pages` branch if needed.
- **Custom Domain:** Set via `static/CNAME`.

---

## 🤝 Contributing

PRs and suggestions are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

- Site content: © Scott Kosman
- Theme: [MIT License](themes/PaperMod/LICENSE) (PaperMod)

---

## 🙏 Acknowledgments

- [Hugo](https://gohugo.io/)
- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod)
- [Original setup guide](https://youngkin.github.io/post/createafreeblogsite/)

---

*Domain registration not included in "free" hosting. Scott has owned this domain since 2003.*