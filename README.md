<!-- @format -->
<!-- markdownlint-disable MD041 -->

![Actions Status](https://img.shields.io/github/actions/workflow/status/SBCSHS/sbcshs-website/ci.yml?style=for-the-badge)
![GitHub Contributors](https://img.shields.io/github/contributors/SBCSHS/sbcshs-website?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/SBCSHS/sbcshs-website?style=for-the-badge)
![Website Status](https://img.shields.io/website?down_color=orange&down_message=Offline&style=for-the-badge&up_color=blue&up_message=Online&url=https%3A%2F%2Fsbcshs.github.io%2Fsbcshs-website%2F)
![Language Count](https://img.shields.io/github/languages/count/SBCSHS/sbcshs-website?style=for-the-badge)

# sbcshs-website

This repository contains the source code for the website for Stone Bridge High School's Computer Science Honor Society.
:desktop_computer:

## Contributing

### Setup

To install all dependencies required to build the site, run

```sh
pip install mkdocs-material mkdocs-git-revision-date-localized-plugin mkdocs-glightbox pillow cairosvg
```

### Adding Images

When adding images, upload the file to `/overrides/assets/images`, then use HTML to add images.

<!-- prettier-ignore -->
```html
<img src="../assets/images/[image]" alt="[title]" width="[num]" height="[num]" align="[alignment]" loading="eager"/>
```

If adding images to index.md, change the `src` attribute to

```sh
"assets/images/[image]"
```

Refer to the [Material for MkDocs documentation](https://squidfunk.github.io/mkdocs-material/) to learn more about Material for MkDocs's capabilities.
