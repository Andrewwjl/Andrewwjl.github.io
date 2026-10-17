# André Wu — personal website

One-page static site. Plain HTML, CSS and a few lines of JavaScript. No build step.

## Files
- `index.html` — the whole site (styles at the top, script at the bottom)
- `assets/` — images and your CV

## Before going live (search index.html for `TODO`)
1. **Headshot** — save as `assets/andre.jpg` (portrait, about 800×1000) and replace the placeholder `<div class="portrait">` with `<div class="portrait"><img src="assets/andre.jpg" alt="André Wu"></div>`.
2. **CV** — export your CV from Overleaf as `assets/Andre_Wu_CV.pdf`.
3. **Information Diffusion link** — add the GitHub link once the repo is public.
4. **Client sites** — ask Romanza and Artur Caneja before naming them publicly; swap the images for real screenshots and add links once live.
5. **CAS photos (optional)** — only photos you're happy to publish; avoid other students' faces.

## Preview locally
Open `index.html` in a browser.

## Publish (GitHub Pages, free)
```
cd "~/MoreLife/人机A区/Anthropic /Personal Website"
git init && git add . && git commit -m "First version of personal site"
git branch -M main
git remote add origin https://github.com/Andrewwjl/andrewwjl.github.io.git
git push -u origin main
```
Create the repo `andrewwjl.github.io` on GitHub first. The site goes live at https://andrewwjl.github.io. A custom domain (e.g. andrewu.com) can be added later in the repo's Pages settings.
