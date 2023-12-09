# Personal website

[![Netlify Status](https://api.netlify.com/api/v1/badges/adf24699-f25e-4a41-894a-1bd833b73bb2/deploy-status)](https://app.netlify.com/sites/imaginative-custard-8fe870/deploys)

This is the source code for my personal website. It is built in R using [postcards](https://github.com/seankross/postcards) with the trestles theme.

## Development

Suggest using the devcontainer in VSCode. This will install all the necessary packages and dependencies via `renv`.

```bash
Rscript -e "rmarkdown::render('index.Rmd')"
```