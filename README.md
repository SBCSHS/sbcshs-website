<!-- @format -->

# sbcshs-website

This repository contains the source code for the website for Stone Bridge High School's Computer Science Honor Society.
:desktop_computer:

# Contributing

To install all dependencies required to build the site, run

```sh
pip install mkdocs-material mkdocs-git-revision-date-localized-plugin mkdocs-glightbox pillow cairosvg
```

When adding images, upload the file to `/docs/images`, then use the link

```sh
"https://raw.githubusercontent.com/SBCSHS/sbcshs-website/main/docs/images/[insert file name]"
```

Use HTML to add images.

<!-- prettier-ignore -->
```html
<img src="[url]" alt="[title]" width="[num]" height="[num]" align="[alignment]" loading="eager"/>
```
