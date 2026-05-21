# ZODS-RS &mdash; Project Page

Project page for **ZODS-RS: Zero-training Oriented Detection &amp; Segmentation for Remote Sensing**.

Live site: <https://gzaicebreak.github.io/zods-rs/>

## Authors

Zuan Gu, Tianhan Gao\*, Langxu Zhao &mdash; Northeastern University, China

## Local preview

This is a plain static site (no build step). Open `index.html` directly in a browser,
or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000/
```

## Layout

```
.
├── index.html                  # main page
├── static/
│   ├── css/style.css
│   ├── images/teaser.jpg       # Figure 1 from the paper
│   ├── images/favicon.svg
│   └── pdfs/ZODS-RS.pdf
├── .nojekyll                   # disable Jekyll on GitHub Pages
├── .gitignore
└── README.md
```

## Credits

Page template adapted from the [Nerfies](https://nerfies.github.io/) project page
(CC-BY-SA 4.0).
