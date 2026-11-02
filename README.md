# Wendy Ma — Personal Portfolio

A fast, responsive, one-page portfolio for GitHub Pages. No framework, build step, or paid services needed.

## Image layout fix

The hero portrait is displayed as the **complete square photo** with `height:auto` and `object-fit:contain` instead of stretching it into an oversized image. It fits entirely inside the page layout on desktop and mobile.

## Publish (GitHub Pages)

1. Create a **public** GitHub repository, e.g. `wendy-portfolio`.
2. Upload `index.html` and the complete `assets/` folder **without changing their relative paths**.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/(root)`, and save.
5. GitHub Pages will show the site's URL (e.g. `https://YOUR-USERNAME.github.io/wendy-portfolio/`).

## Make small edits

- **LinkedIn** is already set to the confirmed profile `https://www.linkedin.com/in/wendy-ma-hm37/`.
- **Build for Illinois** links to `https://illini-builds.github.io/website/`.
- **LiLeMe GitHub / CropMIND deck:** They aren't linked because the exact URLs weren't supplied. In the bottom of `index.html`, find `OPTIONAL_LINKS` and paste their respective `https://` URLs into the quoted empty strings. The links then appear automatically.
- **Email:** currently links to `hm37@illinois.edu`.
- **Photography:** `assets/wendy-portrait.webp` is used in the hero; `assets/wendy-research.webp` is used in About.
- **Projects:** All descriptions live in `index.html` and can be edited in plain text.

## Factual notes

- Build for Illinois is **In progress**, scheduled for Jan 29–31, 2027. Planned outcomes are not presented as completed.
- HCI paper is presented as a **CHI 2027 submission**, not an acceptance.
- CropMIND.ai credits product/data leadership, not personal code implementation.
- The visual panels for projects are decorative graphics, not screenshots of the products.

## Privacy note

This page is public when published. It displays the photos you supplied, your public LinkedIn profile, and your UIUC email address. Remove any element you don't want on a public site before deploying.
