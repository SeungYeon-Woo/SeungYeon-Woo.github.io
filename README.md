# Seung Yeon Woo - Academic Homepage

A build-free, responsive personal research website inspired by Jon Barron. Plain HTML and CSS, with no analytics or third-party runtime dependencies.

## Preview

Run `python3 -m http.server 8765 --bind 127.0.0.1` in this directory, then open http://localhost:8765.

## Update content

- Edit biography, research, experience, and projects in `index.html`.
- Replace `assets/profile-outdoor.png` to update the portrait. Adjust `.portrait` in `style.css` if the new photo needs a different crop.
- Replace `assets/CV_SeungYeon_Woo.pdf` to update the downloadable CV.
- Edit colors, spacing, and responsive layouts in `style.css`.

## Content review

The initial content is based on the supplied CV. Per the owner's update, Visual Computing Lab at SNU (Jul 2026 - Present) is the current internship; Robot Vision Lab and TKU Lab entries are omitted from the website. Confirm the current affiliation, research dates, and expected graduation before publishing. The CV is an unchanged copy of the supplied document and includes its original contact details. The profile photo uses the owner-approved outdoor portrait. AnyCamVLA now includes the full author list, IROS 2026 venue, official project thumbnail, and project/arXiv/PDF/code/video links, verified against the official project page and repository.

## GitHub Pages

Target repository: `SeungYeon-Woo/SeungYeon-Woo.github.io`.
After pushing the reviewed files, select **Settings > Pages > Deploy from a branch**, branch `main`, folder `/ (root)`.
Intended URL: https://seungyeon-woo.github.io/.

## Design credit

Layout inspired by https://jonbarron.info/. Implementation written for this site.

## Research asset attribution

`assets/anycamvla.jpg` is the unmodified CameraAdaptation poster from the AnyCamVLA authors' [official project page](https://heo0224.github.io/AnyCamVLA/), downloaded from `https://heo0224.github.io/AnyCamVLA/assets/images/CameraAdaptation_poster.jpg`. The project page specifies [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The visible publication entry credits all seven authors and links the thumbnail to the source project. Venue verified at https://github.com/heo0224/AnyCamVLA.
