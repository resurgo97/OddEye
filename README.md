# OddEye project page

A static page: `index.html` plus the `assets/` folder. No build step.

## Before publishing

Open `index.html`, find `var LINKS` near the bottom, and fill in:

- `paper`: the arXiv abstract URL
- `arxivId`: the arXiv ID (it is added to the BibTeX)
- `code`: the repository URL

Empty values show as "soon" buttons.

## Hosting on GitHub Pages

1. Put `index.html` and `assets/` at the root of a repository (or in `docs/`).
2. In the repository, open Settings → Pages and choose that branch and folder.

The video is a 720p web encode (14 MB) of `OddEye_explainer_narrated.mp4`.
To use the full 1080p file instead, copy it over `assets/oddeye-explainer.mp4`.
