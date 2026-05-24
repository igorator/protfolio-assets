<div align="center">
  <img src="https://raw.githubusercontent.com/igorator/portfolio-assets/main/banner.png" alt="Portfolio Assets Banner" width="100%" />
</div>

<br/>

<div align="center">

# 📦 portfolio-assets

Static assets repository containing images, screenshots, and CV files  
used across the [portfolio project](https://github.com/igorator/next-portfolio).

![GitHub repo size](https://img.shields.io/github/repo-size/igorator/portfolio-assets?color=6e40c9&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/igorator/portfolio-assets?color=6e40c9&style=flat-square)

</div>

---

## 📁 Repository Structure

```
portfolio-assets/
│
├── banner.png                    # 🖼️  GitHub profile / repo banner
│
├── cv/
│   └── Ihor_Kliushnyk_Frontend_Developer_CV.pdf   # 📄 CV — linked from portfolio
│
└── Projects/                     # 🗂️  Per-project media assets
    ├── <project-name>/
    │   ├── cover.webp            # Main cover shown in the project card
    │   ├── screen-1.webp         # Full-page screenshots (gallery)
    │   ├── screen-2.webp
    │   └── ...
    └── custom-globe/
        └── video.webm            # Demo video (replaces screenshots)
```

---

## 🖼️ Asset Types

| File | Purpose |
|------|---------|
| `cover.webp` | Thumbnail displayed in the project card grid on the portfolio |
| `screen-N.webp` | Detailed screenshots used in the project modal / gallery |
| `video.webm` | Short demo clip shown instead of static screenshots |
| `*.pdf` | Documents linked directly from the portfolio (CV, resume) |
| `banner.png` | Repository / social preview banner |

---

## 🗂️ Projects

**20 projects** — each folder contains a `cover.webp` and optional `screen-N.webp` / `video.webm` files.

---

## 🔗 Usage

Assets are served directly via GitHub's raw content CDN:

```
https://raw.githubusercontent.com/igorator/portfolio-assets/main/Projects/<project>/cover.webp
https://raw.githubusercontent.com/igorator/portfolio-assets/main/cv/Ihor_Kliushnyk_Frontend_Developer_CV.pdf
```

All images are in **WebP** format for optimal performance and small file size.  
Videos are in **WebM** format for broad browser support.

---

<div align="center">
  <sub>Maintained by <a href="https://github.com/igorator">Ihor Kliushnyk</a></sub>
</div>
