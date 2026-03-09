# 🚂 ÖBB Fleet CMS Project
**Status:** Deployed & Grade-Ready ✅

This project is a Jekyll-based Static Site Generator (SSG) implementation for the **CMS System** course module. It showcases the Austrian Federal Railways (ÖBB) fleet through a modern, automated web architecture.

## 📋 Grading Criteria Checklist

| Criterion | Implementation Detail |
| :--- | :--- |
| **Jekyll SSG via GitHub Pages** | Built using Jekyll and hosted on GitHub Pages. |
| **Automatic Deployment** | Configured via **GitHub Actions**; triggers on every `git push`. |
| **3+ Distinct Pages** | `index.md`, `railjet.md`, and `specs.md` with internal linking. |
| **Syntax Highlighting** | Python code block used in `specs.md` to show fleet calculations. |
| **Local Image Embedding** | Featured in `railjet.md` via the `/assets/` directory. |
| **Snazzy Theme** | Utilizes the `jekyll-theme-midnight` for a dark, high-tech aesthetic. |

---

## 🏗️ Technical Architecture

### 1. CMS Workflow
This project utilizes a **File-based CMS** approach. Content is authored in Markdown, structured with YAML Front Matter, and transformed into high-performance static HTML.

### 2. Assets & Media
Local images are stored in the `/assets/` directory and called using Liquid tags to ensure path persistence across different environments:
`![Description]({{ site.baseurl }}/assets/image.jpg)`

### 3. Logic & Calculations
To demonstrate the "Technical Specs" capability, a Python snippet is included to illustrate how fleet power-to-weight ratios are calculated for the Siemens Taurus locomotives.

---

## 🚀 How to Run Locally

1. Clone the repository:
   `git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git`
2. Install dependencies:
   `bundle install`
3. Start the Jekyll server:
   `bundle exec jekyll serve`
4. Open your browser at `http://localhost:4000`

---

## ✍️ Author
**[Your Name/Student ID]** *Part of the CMS System Course - 10% Grade Weight*