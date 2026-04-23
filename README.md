# MKT3039 – Assessment 2 E-Portfolio

**The LEGO Group: Digital Marketing Portfolio**

A critical evaluation of engagement, social media, owned media, and emerging trends in the toy industry.

---

## About

This repository hosts the web version of my MKT3039 Assessment 2 e-portfolio, written as a critical analysis of The LEGO Group's digital marketing strategy. The portfolio is structured around four entries:

1. **The Ladder of Engagement** — applying Smith and Zook's (2016) framework to LEGO.com and LEGO Ideas.
2. **Evaluation of Social Platform** — assessing LEGO's TikTok presence against Tuten and Solomon's (2018) Four Zones of Social Media.
3. **Website Evaluation** — a scored checklist of LEGO.com against Nielsen Norman Group, Baymard Institute, and Chaffey and Ellis-Chadwick benchmarks.
4. **Trend Analysis** — augmented reality and the connected physical product, analysed through the RACE framework.

## Author

**Anh Quan Dang**
Student ID: 25831838
Module: MKT3039 – Digital Marketing
University of Northampton
April 2026

## Live Site

Once GitHub Pages is enabled on this repository, the portfolio will be available at:

```
https://<your-github-username>.github.io/<repository-name>/
```

## Setup – Hosting on GitHub Pages

1. **Create a new repository** on GitHub (public, so Pages is free).
2. **Upload both files** (`index.html` and `README.md`) to the root of the repository.
   - Either use the GitHub web UI ("Add file → Upload files"), or push from Git locally.
3. **Enable GitHub Pages**:
   - Go to **Settings → Pages**.
   - Under "Source", select the `main` branch and the `/ (root)` folder.
   - Click **Save**.
4. **Wait 1–2 minutes**. GitHub will publish the site at the URL shown in the Pages settings panel.

No build step is required — the portfolio is a single self-contained HTML file with CSS in a `<style>` block and fonts loaded from Google Fonts.

## File Structure

```
.
├── index.html     # The portfolio (single-file site)
└── README.md      # This file
```

## Figures

The portfolio includes 16 figure placeholders (hatched boxes with captions). To replace a placeholder with a real image:

1. Add the image file to the repository (e.g., in an `images/` folder).
2. In `index.html`, find the matching `<div class="fig-placeholder">...</div>` and replace it with:

   ```html
   <img src="images/your-image.jpg" alt="Descriptive alt text">
   ```

The existing `figure` CSS will automatically apply the shadow, border, and centering.

## Design

- **Typography:** Playfair Display (headings) and Source Serif 4 (body), loaded from Google Fonts.
- **Palette:** Warm editorial tones — burnt sienna accent, amber highlight, cream paper, tan rules.
- **Layout:** 900px max-width centred column, sticky top navigation, responsive down to mobile.
- **Accessibility:** Semantic headings (h1–h4), in-page anchor links, sufficient colour contrast.

## Licence

Academic work submitted for assessment at the University of Northampton. All cited sources belong to their respective authors; please see the References section of the portfolio for full attribution.
