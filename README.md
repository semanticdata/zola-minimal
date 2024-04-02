# 📚 Minimal

<p align="">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-minimal" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-minimal" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-minimal" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-minimal" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/zola-minimal.svg" />
</p>

[Minimal](https://zola-minimal.vercel.app/) is a [Zola](https://www.getzola.org) theme with the goal of helping you build a light, fast, and SEO ready landing page or website. It is based on the [Jekyll](https://jekyllrb.com/) theme with [the same name](https://github.com/pages-themes/minimal).

Check out the [demo](https://zola-minimal.vercel.app/).

## Table of Contents

- [📚 Minimal](#-minimal)
  - [Table of Contents](#table-of-contents)
  - [Screenshots](#screenshots)
  - [Getting Started](#getting-started)
  - [Configuration](#configuration)
  - [Reporting Issues](#reporting-issues)
  - [Attributions](#attributions)
  - [License](#license)

## Screenshots

![theme screenshot](screenshot.png)

## Getting Started

Tips that will help you develop and preview the site locally.

### Requirements

Before using the theme, you need to install [Zola](https://www.getzola.org/documentation/getting-started/installation/) ≥ 0.18.0.

### Quick Start

```sh
# Clone the repo
git clone git@github.com:semanticdata/zola-minimal.git

# Change directory into the cloned folder
cd zola-minima

# Serve the site locally
zola serve

# Open http://127.0.0.1:1111/ in the browser
```

For more detailed instructions, visit the [Documentation](https://www.getzola.org/documentation/themes/installing-and-using-themes/) page about installing and using themes.

### Useful Commands

A short list of commands that will help you develop your own version of the theme.

| Command                 | Description            |
| ----------------------- | ---------------------- |
| `zola init <repo-name>` | Initiate new Zola site |
| `zola build`            | Build only             |
| `zola serve`            | Build and Serve        |

## Configuration

You can changed the configuration, templates and content yourself. Refer to the `config.toml`, and templates files for ideas. In most cases you only need to modify the contents of `config.toml` to customize the appearance of your blog. Make sure to visit the [Zola Documentation](https://www.getzola.org/documentation/getting-started/overview/).

### Custom CSS Styles

Adding custom CSS is as easy as adding your styles to `sass/_custom.scss`. This is made possible because SCSS files are backwards compatible with CSS. This means you can type normal CSS code into a SCSS file and it will be valid.

## Reporting Issues

We use GitHub Issues as the official bug tracker for **Minimal**. Please
search [existing issues](https://github.com/semanticdata/zola-minimal/issues). It’s possible someone has already reported the same problem.

If your problem or idea is not addressed yet, [open a new issue](https://github.com/semanticdata/zola-minimal/issues/new).

## Attributions

Zola Minimal is a fork of the Jekyll theme [Minimal](https://github.com/pages-themes/minimal).

## License

Source code in this repository is available under the [MIT License](LICENSE).
