# Cookiecutter template for Beamer
[![pipeline status](https://git.jinr.ru/treskov/cookiecutter-beamer/badges/master/pipeline.svg)](https://git.jinr.ru/treskov/cookiecutter-beamer/-/commits/master)

Easy and fast way to bootstrap a Beamer presentation without tedious process of copying style files and other
configuration between presentations with [cookiecutter](https://github.com/cookiecutter/cookiecutter).

> Requires [Lato font](https://fonts.google.com/specimen/Lato#standard-styles)

## How it looks like
- [last successfully built PDF](http://treskov.pages.jinr.ru/cookiecutter-beamer/talk.pdf)

## Install cookiecutter
```shell
pip install cookiecutter
```

## Bootstrap presentation:
The following command creates:
-  sample Beamer presentations
-  git repo
-  .latexmkrc
-  git pre-commit-hooks
-  GitLab CI config for continuous build of slides
settings and git hooks
```
cookiecutter https://git.jinr.ru/treskov/cookiecutter-beamer
```

## Useful Latexmk commands
### Build slides
```bash
latexmk
```

### Clean intermediate files
```bash
latexmk -c
```

### Force rebuiding
```bash
latexmk -gg
```
## Source of inspiration
Based on Saarland theme
https://github.com/kailashbuki/beamerthemesaarland


