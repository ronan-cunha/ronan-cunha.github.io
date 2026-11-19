# ronancunha.github.io

Personal academic website built with pure semantic HTML5 and CSS3 (zero build dependencies, instant deployment on GitHub Pages).

## Repository Structure

```text
ronancunha.github.io/
├── index.html        # Home page (bio, affiliations, academic links, selected research)
├── research.html     # Working papers, ongoing projects, and publications
├── teaching.html     # Courses and academic coordination at FGV RI
├── software.html     # R packages (tsanalysis) and interactive Shiny labs
├── cv.html           # Curriculum Vitae summary + PDF download button
├── styles.css        # Responsive academic editorial stylesheet
├── cv.pdf            # [Add your PDF CV here]
└── images/
    ├── portrait.jpg  # [Add your portrait photo here, 4:5 aspect ratio recommended]
    └── banner.jpg    # [Optional header banner photo, e.g. 1600x400px]
```

## How to Publish on GitHub Pages

1. Create a public repository on GitHub named **`ronancunha.github.io`** (under your GitHub username `ronancunha` — note: if your GitHub username is `ronan-cunha`, name the repository `ronan-cunha.github.io` or configure a custom domain).
2. Add your files:
   - Place your photo at `images/portrait.jpg` (and optionally `images/banner.jpg`, uncommenting the `<img>` tag in `index.html`).
   - Place your PDF CV at `cv.pdf` in the root folder.
   - Update your Google Scholar and Lattes URLs in `index.html`, plus your working papers/publications in `research.html`.
3. Push everything to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial academic website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```
4. In GitHub, go to **Settings → Pages**, ensure **Source** is set to **Deploy from a branch** (`main` / `/ (root)`), and save. Your site will be live within ~1 minute.
