# LUC CS Academics Website

> The official Loyola University Chicago Computer Science academic offerings website

![GH Pages Deployment](https://github.com/LoyolaChicagoCS/coursedescriptions/actions/workflows/main.yml/badge.svg)

## Where is This Site Located?

This site can be found at https://academics.cs.luc.edu

## How to Contribute

### Filing Issues

If you spot any issues with the site, feel free to open an issue at https://github.com/LoyolaChicagoCS/coursedescriptions/issues

### Developing Using Sphinx

If you want to develop this site further follow the steps below:

1. Install `Python 3.9+`
2. Run `pip install -r requirements.txt`

## Deploying Site to GitHub Pages

If you wish to deploy the site to GitHub Pages, a GitHub Action workflow has already been made to simplify this process.

1. Enable `Actions` on your fork of this project
2. Enable `GitHub Pages` on your fork of this project
3. If you use a different production branch name other than `main`, change the [workflow](.github/workflow/main.yml) to point to that branch
