# Kim Seojin's Academic Website

A static personal academic website based on [Jon Barron's original website source](https://github.com/jonbarron/jonbarron.github.io), preserving its minimal layout.

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000/>.

## GitHub Pages

- Repository: <https://github.com/Se0jin-Kim/Se0jin-Kim.github.io>
- Website URL: <https://se0jin-kim.github.io/>
- Publishing source: **Deploy from a branch**, **main**, **/ (root)**.
- `index.html` is the entry point; `.nojekyll` preserves the static HTML and assets without Jekyll processing.
- No custom domain is configured. The original template's `CNAME` is not used.

## Files

- `index.html`: homepage content and section structure.
- `stylesheet.css`: typography and responsive layout.
- `images/KimSeojin.jpg`, `images/yonsei-symbol.jpg`, and `images/projects/`: personal website images and project animations.
- `data/KIMSEOJIN_CV.pdf`: linked CV.

## Retained template pages

The standalone `mipnerf/`, `mipnerf360/`, `zipnerf/`, and `softmaxfix/` pages and their local dependencies remain intact. They are original template projects, separate from the personal homepage.

Unused publication and miscellaneous content, hover scripts, and unreferenced root assets have been removed from the current homepage. The original source remains available in Git history and through the `upstream` remote.

The homepage uses plain HTML/CSS and native GIF playback; no JavaScript build step or package installation is required. Keep personal assets referenced by `index.html`, and check dependencies of the retained pages before removing any other files.
