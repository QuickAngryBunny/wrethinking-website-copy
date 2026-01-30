# Wrethinking Website – Static Copy

A 1:1 static replica of [wrethinking.org](https://wrethinking.org/) with the same HTML structure and CSS layout.

## Pages

- **index.html** – Home
- **what-we-do.html** – What We Do
- **presently-supporting.html** – Presently Supporting
- **our-founders-and-directors.html** – Our Founders and Directors
- **collaborate-with-us.html** – Collaborate With Us

## Assets

- **public/** – All images and stylesheets
  - **2020/12/**, **2021/01/**, **2021/02/**, **2021/04/** – Images (logos, photos, icons)
  - **elementor/css/** – Elementor page CSS (post-5, post-10, post-11, post-14, post-15, post-16, post-19, post-205, global.css)
  - Root CSS – block-library, style, frontend, contact-form-7, sccss, etc.

## How to view

1. **File:** Open `index.html` in a browser (some assets may need a local server due to path/security).
2. **Local server (recommended):**
   ```bash
   cd /path/to/wrethinking-website-copy
   python3 -m http.server 8000
   ```
   Then open http://localhost:8000

## Structure

- HTML and CSS match the original site’s layout and design.
- Internal links use relative paths (e.g. `what-we-do.html`).
- Images and CSS are loaded from the `public/` folder.
- Contact form and other scripts are present but will not submit; the copy is static.
