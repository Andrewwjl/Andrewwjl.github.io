# André Wu — personal website

One-page static site. Plain HTML, CSS and a few lines of JavaScript. No build step.

## Files
- `index.html` — the whole site (styles at the top, script at the bottom)
- `assets/` — images and your CV

## Before going live (search index.html for `TODO`)
1. **Headshot** — replace `assets/andre.jpg` with a professional photo when you have one (same name, portrait 4:5).
3. **Information Diffusion link** — add the GitHub link once the repo is public.
4. **Client sites** — swap the images for real screenshots and add links once live.
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
