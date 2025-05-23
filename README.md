# TeXLive AltaCV Builder Image

A minimal, reusable Docker image for compiling AltaCV template based LaTeX CVs with TeXLive on Debian Bookworm.

## Features

- Based on `debian:bookworm-slim`
- TeXLive (scheme-small) with selected CV-related packages
- Locale and timezone preconfigured (en_US.UTF-8 and Europe/Berlin)
- Fonts: Lato, Roboto Slab

## Included TeX Packages

The following TeX Live packages are installed in the image using `tlmgr`:

- `accsupp`
- `adjustbox`
- `biber`
- `biblatex`
- `changepage`
- `csquotes`
- `dashrule`
- `enumitem`
- `environ`
- `fontawesome5`
- `ifmtarg`
- `latexmk`
- `multirow`
- `paracol`
- `pdfx`
- `tcolorbox`
- `tikzfill`
- `titlesec`
- `xmpincl`

These packages are sufficient for building modern LaTeX CVs based on popular templates like AltaCV.

## DockerHub Repository

```bash
https://hub.docker.com/r/sksdotsauravs/altacv_builder_debian_texlive
```
