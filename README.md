<div align="center">

# Blog website

**A travel blog with 33 posts, six categories and a custom Destinations taxonomy, built in WordPress.**

[![Live demo](https://img.shields.io/badge/Live%20demo-open-2d4a7c?style=for-the-badge)](https://evanexanes.github.io/blog-website/)
[![Case study](https://img.shields.io/badge/Case%20study-read-555555?style=for-the-badge)](https://evanexanes.github.io/03-case-study-blog.html)

![WordPress](https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white)
![Blocksy](https://img.shields.io/badge/Theme-Blocksy-2d4a7c)
![Format](https://img.shields.io/badge/This%20repo-static%20export-555555)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-2d4a7c.svg)](LICENSE)

<img src="docs/screenshot.webp" alt="The travel blog home page with its search bar over a waterfall photo" width="860">

</div>

## Contents
- [About](#about)
- [Stack](#stack)
- [What this repository is](#what-this-repository-is)
- [What works in the static copy](#what-works-in-the-static-copy)
- [License](#license)
- [Author](#author)

## About
A travel blog with 33 posts, six categories and a custom Destinations taxonomy. Post titles are real places, and the article text is placeholder. It is a self-initiated WordPress practice build.

## Stack

| Part | Tool |
|---|---|
| CMS | WordPress |
| Theme | Blocksy |
| Custom taxonomy | Custom Post Type UI |
| Mailing list and forms | Newsletter, Contact Form 7 |

## What this repository is
A static copy of the WordPress site, exported with Simply Static so it can run on GitHub Pages. It is generated HTML, CSS and JavaScript, not the WordPress source: there is no PHP, database or `wp-config.php` here.

Each exported page opens with a documentation header (program name, description, author and a history table). The files are generated, so they are not meant to be edited by hand: change the site in WordPress, export it again and add a history row. The page list, theme and plugins are in [docs/DOCUMENTATION.md](docs/DOCUMENTATION.md).

## What works in the static copy
GitHub Pages cannot run PHP, so anything that needs the WordPress server does not work in this copy. The newsletter sign-up and the Advertise form send through Web3Forms. Search and comments need WordPress and say so when used.

## License
WordPress, the theme and the plugins are each released under the GNU General Public License, version 2 or later or version 3, as each one states. This repository as a whole is released under the [GNU General Public License, version 3](LICENSE), which all of them allow. The sample text and pictures are placeholder content for a practice build.

## Author
**Evan Prens P. Exanes** · [GitHub](https://github.com/evanexanes) · [Portfolio](https://evanexanes.github.io/)
