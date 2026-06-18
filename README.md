# Albert Zhang — Network Engineer Portfolio

A single-page portfolio site, ready for GitHub Pages.

## Folder structure
```
portfolio/
├── index.html        ← the whole site (HTML + CSS + JS in one file)
└── docs/              ← lab write-ups as PDFs, linked from the Documents section
    ├── Multi-Area-OSPF-Lab.pdf
    ├── BGP-Documentation.pdf
    ├── AWS-Cloud-Foundations-Labs.pdf
    ├── Ethical-Hacking-Lab-Ettercap.pdf
    ├── Local-LLM-Lab.pdf
    └── Windows-11-Installation.pdf
```

## Putting it on GitHub
1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload everything in this folder — `index.html` and the `docs` folder — to the root of that repository.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment," set Source to **Deploy from a branch**, pick the `main` branch and `/ (root)` folder, then save.
5. GitHub will give you a live URL, usually `https://yourusername.github.io/portfolio/`, within a minute or two.

## Things to personalize before publishing
- Swap `your.email@example.com`, the GitHub link, and the LinkedIn link in the **Contact** section for your real ones.
- Add or remove project cards in the **Projects** section as you build more labs.
- To add another document: drop a PDF into `docs/`, then copy one of the `<div class="doc-card">` blocks in `index.html` and point its link at the new file.

## Notes on the features added
- **Custom cursor** — a ring follows the mouse with a slight ease; it's disabled automatically on touch devices and when the visitor has "reduce motion" turned on at the OS level.
- **Scroll motion blur** — the page blurs slightly based on how fast you scroll, then sharpens once it settles. Also respects reduced-motion settings.
- **Vertical stacking** — Projects and Documents are single-column stacks with generous section padding, so the page reads top-to-bottom rather than spreading into a grid.
