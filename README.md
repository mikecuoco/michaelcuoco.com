# Personal website

This is the source code for my personal website. It is built in R using [postcards](https://github.com/seankross/postcards) with the trestles theme.

## Development

Suggest using the devcontainer in VSCode. This will install all the necessary packages and dependencies via `renv`.

```bash
Rscript -e "rmarkdown::render('index.Rmd')"
```