README - Nivvayasa site (fixed for GitHub Pages)

What I changed:
- Replaced local `lib/...` references in HTML files with CDN links for Owl Carousel, Animate.css, and WOW.
- Added a minimal js/main.js to avoid missing-JS errors and initialize libraries if present.
- Ensured references to css/style.css and images are unchanged.

How to publish:
1. Create a GitHub repository (public).
2. Upload all files/folders inside this project root (index.html, about.html, css/, images/, js/, etc.) — do NOT include an extra parent folder.
3. In the repo -> Settings -> Pages choose branch `main` and folder `/ (root)`.
4. Your site will be live at: https://yourusername.github.io/reponame/

If you want, I can also:
- Add local copies of Owl Carousel and WOW instead of using CDN (safer offline).
- Improve responsiveness and UI polish further.
