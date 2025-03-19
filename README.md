This repo contains the course files and resources for *BIOB11: Experimental Design and Analysis for Biologists* (2025).

The site makes heavy use of [R for WebAssembly](https://github.com/r-wasm) to enable interactive teaching examples in a static website framework.

# Dependencies
- Requires [Quarto v1.6+](https://quarto.org/)
- Requires [R](https://www.r-project.org/)

## Quarto extensions
- [`quarto-countdown`](https://github.com/gadenbuie/countdown/tree/main/quarto)
- [`quarto-live`](https://github.com/r-wasm/quarto-live)
- [`attribution`](https://github.com/quarto-ext/attribution)

# Usage

The repo is setup as a [Quarto Project](https://quarto.org/docs/projects/quarto-projects.html), using the [website template](https://quarto.org/docs/websites/).

To build the site, install the required quarto extensions in the root directory (see links above for source code):

```{bash}
quarto add gadenbuie/countdown/quarto
quarto add r-wasm/quarto-live
quarto add quarto-ext/attribution
```

You can then build the site, which is built in `/_site` folder:

```{bash}
quarto render
```

# Attributions

- [`slides/slides.scss`](slides/slides.scss) is forked from the revealjs theme: [`grantmcdermott/quarto-revealjs-clean`](https://github.com/grantmcdermott/quarto-revealjs-clean)

# To contribute

Create a pull request or issue.