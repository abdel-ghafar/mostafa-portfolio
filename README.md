# Mostafa Abdelghafar Portfolio Website

A responsive static portfolio prepared for GitHub Pages.

## Files
- `index.html`: page content and structure
- `styles.css`: responsive visual design
- `script.js`: menu, reveal animation, and footer year
- `assets/Mostafa-Abdelghafar-CV.pdf`: downloadable CV
- `assets/dashboards/`: place your dashboard screenshots here

## Replace the dashboard samples
1. Export each dashboard page as a high-quality PNG or WebP at 1600 x 900 or similar 16:9 size.
2. Save the files as:
   - `assets/dashboards/dashboard-01.webp`
   - `assets/dashboards/dashboard-02.webp`
   - `assets/dashboards/dashboard-03.webp`
3. In `index.html`, replace each block that starts with `<div class="project-visual dashboard-placeholder ...">` with:

   `<div class="project-visual"><img src="assets/dashboards/dashboard-01.webp" alt="Executive export performance Power BI dashboard"></div>`

4. Repeat for images 02 and 03, changing the alt text to describe each dashboard.
5. Do not publish confidential customer names, prices, account data, or internal company figures. Use blurred, masked, or demo data where needed.

## Publish on GitHub Pages
1. Create a public GitHub repository, for example `mostafa-portfolio`.
2. Upload the *contents* of this folder to the repository root.
3. Open repository **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. GitHub will show the live portfolio URL after deployment.

## Before publishing
- Replace dashboard placeholders.
- Check every external link.
- Consider whether to keep the phone number only in the CV or add it to the contact section.
- Add a custom domain later if desired.

## Version 2 additions
- Professional journey gallery with supplied photos.
- Six selected LinkedIn thought-leadership posts.
- Hero professional speaking image.
