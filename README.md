---
title: "Readme"
author: "Tim Finney"
date: "13 October 2017"
output: html_document
---

# Fresh Start web site development

This is a development area for a new FreshStart website. See [the existing website](http://www.freshstart.org.au/).

See [Up and running with blogdown](https://apreshill.rbind.io/post/up-and-running-with-blogdown/) for a guide.

# Create fresh-start repository on GitHub

Use GitHub to create a new `fresh-start` repository with a Readme but nothing else.

# Clone fresh-start repository

`cd ~/Keep/www/freshstart.com.au/mk2`

`git clone https://github.com/tjfinney/fresh-start.git`

There is now a `fresh-start` directory at `~/Keep/www/freshstart.com.au/mk2/fresh-start`.

# Create new R project

Use the top menu buttons in RStudio to select File -> New Project -> Existing Directory, browse to the `fresh-start` directory, then click on the Create Project button.

Edited `.gitignore`.

# Create new site

`blogdown::new_site(theme = "devcows/hugo-universal-theme", theme_example = TRUE)`

(Had to move Readme.md and .html to another place before doing this.)

Uncheck a couple of [project options](https://bookdown.org/yihui/blogdown/rstudio-ide.html#fig:project-options).

# Push to GitHub

Using RStudio's Git interface, use checkboxes to add files and directories, commit, then push to GitHub by pressing the Push button.

# Deploy with Netlify

Go to Netlify and [deploy](https://app.netlify.com/sites/freshstart/deploys). This assumes that Netlification has already been done.
