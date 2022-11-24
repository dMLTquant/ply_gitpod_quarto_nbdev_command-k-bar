# ply_gitpod_quarto_nbdev_command-k-bar
Playground: Create a Command K Bar (with Search) for a Quarto (nbdev) Website

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/dMLTquant/ply_gitpod_quarto_nbdev_command-k-bar)

![image](https://user-images.githubusercontent.com/61799047/203839248-3e1a9127-278b-4baa-bde5-5af5bd804de4.png)

## Quarto

> [Quarto®](https://quarto.org/) is an open-source scientific and technical publishing system built on Pandoc
>
> - Create dynamic content with Python, R, Julia, and Observable.
> - Author documents as plain text markdown or Jupyter notebooks.
> - Publish high-quality articles, reports, presentations, websites, blogs, and books in HTML, PDF, MS Word, ePub, and more.
> - Author with scientific markdown, including equations, citations, crossrefs, figure panels, callouts, advanced layout, and more.

## nbdev

> [nbdev.fasti.ai](https://nbdev.fast.ai/) Create delightful software with Jupyter Notebooks
>
> Write, test, document, and distribute software packages and technical articles — all in one place, your notebook.

### Documentation Only Sites

> How to create nbdev powered docs without a library!
> 
> While nbdev is great for authoring software, you may wish to utilize the power of nbdev for the purposes of documenting existing code, or use various utilities of nbdev without having to write a python library.
> 
> More information: [nbdev.fast.ai/tutorials/docs_only.html](https://nbdev.fast.ai/tutorials/docs_only.html)
> Demo: A minimal example of a documentation-only site is located [github.com/hamelsmu/nolib_nbdev](https://github.com/hamelsmu/nolib_nbdev)

#### Setup

> To setup a documentation only site, you can follow these steps:
> 
> - Create a nbdev repo the usual way, using [nbdev_new](https://nbdev.fast.ai/api/cli.html#nbdev_new)
> - Remove library files: `rm setup.py .github/workflows/test.yaml nbs/00_core.ipynb`
> - Remove your library folder (this will be the lib_path field in settings.ini): `rm -rf <lib_path>`
