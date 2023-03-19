<!-- @format -->
<!-- markdownlint-disable MD041 -->

![GitHub contributors](https://img.shields.io/badge/Contributors-5-brightgreen)

# sbcshs-website

This repository contains the source code for the website for Stone Bridge High School's Computer Science Honor Society.
:desktop_computer:

# Contributing

To install all dependencies required to build the site, run

```sh
pip install mkdocs-material mkdocs-git-revision-date-localized-plugin mkdocs-glightbox pillow cairosvg
```

When adding images, upload the file to `/overrides/assets/images`, then use HTML to add images.

<!-- prettier-ignore -->
```html
<img src="../assets/images/[image]" alt="[title]" width="[num]" height="[num]" align="[alignment]" loading="eager"/>
```

If adding images to index.md, change the src attribute to

```sh
"./assets/images/[image]"
```

Refer to the [Material for MkDocs documentation](https://squidfunk.github.io/mkdocs-material/) to learn more about Material's capabilities.
