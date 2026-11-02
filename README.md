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
- **LiLeMe GitHub:** now linked to `https://github.com/hm37-blip/Li-Le-Me`. The visual uses the supplied penguin mascot. Note that the public repo currently highlights product documentation; do not imply visitors can run the WeChat app directly in a desktop browser.
- **Build for Illinois:** card displays the provided screenshot and clicks through to `https://illini-builds.github.io/website/`.
- **CropMIND deck:** still not linked; paste its URL into `OPTIONAL_LINKS.cropmindDeck` when ready.
- **Email:** currently links to `hm37@illinois.edu`.
- **Photography:** `assets/wendy-portrait.webp` is used in the hero; `assets/wendy-research.webp` is used in About.
- **Projects:** All descriptions live in `index.html` and can be edited in plain text.

## Factual notes

- Build for Illinois is **In progress**, scheduled for Jan 29–31, 2027. Planned outcomes are not presented as completed.
- HCI paper is presented as a **CHI 2027 submission**, not an acceptance. No unpublished figure, exact paper title, or confidential research finding is disclosed.
- CropMIND.ai credits product/data leadership, not personal code implementation.
- LiLeMe and Build for Illinois now use user-supplied real project imagery; other visuals remain illustrative.

## Privacy note

This page is public when published. It displays the photos you supplied, your public LinkedIn profile, and your UIUC email address. Remove any element you don't want on a public site before deploying.

## Sacks Lab research card (v5)

- The AgTech project appears **only on the homepage** as an ongoing Sacks Lab study.
- The card shows the supplied preliminary correlation graphic, but does not link to a separate case-study page.
- DNA results are pending. Do not describe the study as published, complete, or genetically validated until those results are available.
- `agtech-salinity.html` and `assets/agtech-clustering.webp` have been removed from this package.
- **Important:** if you uploaded the old case-study page to GitHub, delete `agtech-salinity.html` from the repository too. Merely uploading this new `index.html` does not delete a previously published URL.

## Updating an existing GitHub Pages repository

1. Upload/replace the root `index.html` with the new one. The existing `assets/agtech-correlation.webp` may remain unchanged.
2. If the old `agtech-salinity.html` is in the repository, click it, select the trash/delete option, and commit the deletion.
3. GitHub Pages will redeploy from the existing main branch; no Pages settings need to be changed.
