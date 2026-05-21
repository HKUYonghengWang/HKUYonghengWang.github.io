# Yongheng Wang - Academic Website

This repository hosts the source files and deployed static pages for the academic website of **Yongheng Wang**, a Ph.D. candidate in Electrical and Computer Engineering at **The University of Hong Kong**.

Website: [https://hkuyonghengwang.github.io/](https://hkuyonghengwang.github.io/)

## About

The website presents research interests, publications, projects, software, notes, academic service, and contact information. The current research focus is on:

- small-signal stability analysis and control of converter-dominated power systems;
- passivity- and dissipativity-based methods for power-electronic-interfaced networks;
- planning and operation of active distribution networks with renewable energy, energy storage, and electric vehicles.

## Repository Structure

```text
www/                    Jemdoc source files and menu configuration
html/                   Generated static website served by GitHub Pages
html/static/            CV, notes, software packages, and other static files
.github/workflows/      GitHub Pages deployment workflow
jemdoc.py               Jemdoc generator used by the site
```

## Updating the Website

Edit the source files in `www/`, then regenerate the static pages:

```bash
cd www
python2 ../jemdoc.py -c jemdoc.conf -o ../html/ *.jemdoc
```

Preview the generated pages in `html/`, commit both the source and generated HTML files, and push to `main`. GitHub Pages deploys the committed static site automatically.

## Notes

This repository is maintained primarily as an academic website rather than a general-purpose software package. Research software is listed on the website's [Softwares](https://hkuyonghengwang.github.io/software.html) page and, when appropriate, in separate GitHub repositories.
