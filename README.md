# ALP-aca website

## Creating the site

The site is created using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). You will have to install

```bash
pip install mkdocs-material
```

The pages are written in markdown format, with the possibility of adding TeX and other extra effects (see the documentation in the above link). All pages are in the `docs/` directory.

Blog entries are stored in the directory `docs/blog`. At the beginning of the markdown file of each blog entry, fill the metadata like this:

```yaml
---
title: ALP-aca v1.1
date: 2025-10-31
authors: [Alpaca]
categories: [updates]
---
```

The available authors are defined in `docs/blog/.authors.yaml`.

In order to see a local live preview of the site, run

```bash
mkdocs serve
```

When everything is ready, run

```bash
mkdocs build
```

which will generate the folder `site/` with the contents of our site converted to HTML format.

## Publishing

You will have to first install

```bash
npm install --global surge
```

Then simply run

```bash
surge site/
```

you'll be asked the domain name, make sure it is correctly spelled `alpaca-alps.surge.sh`. And that's all!
