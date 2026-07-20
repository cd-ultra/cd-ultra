# cd-ultra

A developer splash page — a small archive of browser-native tools I've built,
each with a screenshot, a short write-up, and links to the live demo and source.

**Live site:** https://cd-ultra.github.io/cd-ultra/

## Featured projects

| Project | What it is | Live | Source |
|---------|------------|------|--------|
| **WebCut** | A no-install, local-first non-linear video editor (WebGPU / WebCodecs) | [demo](https://cd-ultra.github.io/WebCut/) | [repo](https://github.com/cd-ultra/WebCut) |
| **BlobTune** | An educational, from-scratch Melodyne-style pitch editor (Web Audio, zero deps) | [demo](https://cd-ultra.github.io/BlobTune/) | [repo](https://github.com/cd-ultra/BlobTune) |

## Structure

```
index.html        # the splash page
css/style.css     # styling (dark, self-contained, no external assets)
assets/           # project screenshots (real captures of the live apps)
.nojekyll         # serve files as-is on GitHub Pages
```

Plain static HTML/CSS — no build step and no external dependencies, so it
loads instantly and works offline.

## Publishing on GitHub Pages

**Settings → Pages → Build and deployment → Source: Deploy from a branch**,
then pick the branch that holds this page and `/ (root)`. Every push
republishes automatically.
