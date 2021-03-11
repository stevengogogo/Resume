# Resume - A latex template




- Publication: [`doc`](https://github.com/stevengogogo/Resume/tree/doc) branch
- Single page version: [`one-page`](https://github.com/stevengogogo/Resume/tree/one-page) branch


## Usage

This template uses [tectonic](https://github.com/tectonic-typesetting/tectonic) for compiling `.tex` files. To generate the PDF output, just simply type:

```bash
make build
```

## Prerequisite

- Linux / MacOS
- conda
- tectonic

## installation

- install conda
- install tectonic
    ```bash
    conda install tectonic
    ```

## Features

- Easy build
- Github CI : early diagnose a bug in tex file / reproducible environment

## Why tectonic?

I had used AltaCV with `lualatex` for a while, but soon frustrating with complicated installation which makes it really hard to deploy this template on individual laptop. Though Overleaf is a pormising solution for compiling the tex file, the online platform doesn't support all the branch in git - only for master branch. This is quite annoying when frequent changes in single branch without proper version control. The tectonic is the final solution, it can execute tex file in simple command via auto managing the package installation.


## Manual of `AtlasCV`

- See [`liantze/AtlaCV`](https://github.com/liantze/AltaCV)
- [manual](https://github.com/stevengogogo/Resume/issues/3)

