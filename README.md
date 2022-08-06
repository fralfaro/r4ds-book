# R for Data Science

![example workflow](https://github.com/fralfaro/r4ds-book/actions/workflows/documentation.yml/badge.svg)
<a href="https://fralfaro.github.io/r4ds-book/"><img alt="Link a la Documentación" src="https://img.shields.io/badge/docs-link-brightgreen"></a>

This repository contains the source of R for Data Science book. The book is built using [mkdocs](https://www.mkdocs.org/).

> **Note**: this repository is an alternative to the official [r4ds](https://github.com/hadley/r4ds) documentation.

## Repository Description

The repository has the following folders and files:

```
|
+--- .github
|   \--- workflows
|           documentation.yml
|
\--- docs
|   \--- data
|           **.csv
|           **.xlsx
|   \--- images
|           **.png
|           **.jpg
|   \--- **.ipynb
|           
|   .gitignore
|   contribs.txt
|   LICENSE
|   mkdocs.yml
|   poetry.lock
|   pyproject.toml
|   README.md
```

where:

* `.github/workflows/documentation.yml`: generate documentation with Github Actions.
* `docs/data`: `.csv` and `.xlsx` file for examples.
* `docs/images`: images in `.png` and `.jpg` format.
* `docs/**.ipynb`: all jupyter notebooks  with R kernel.
* `.gitignore`: is a text file that tells Git which files or folders to ignore in a project.
* `contribs.txt`: project contributors [hadley/r4ds/](https://github.com/hadley/r4ds/).
* `LICENSE`: open source license.
* `mkdocs.yml`: mkdocs settings are always configured by using this file.
* `poetry.lock`: [poetry](https://python-poetry.org/) file for python dependencies.
* `pyproject.toml`: [poetry](https://python-poetry.org/) file for python dependencies.
* `README.md`: this file contains the repository name and some basic instructions.

