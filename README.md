### R for Research: Introduction to good practices

These materials were developed for an LSHTM workshop introducing good practices using R for research.

- View [workshop slides](https://docs.google.com/presentation/d/1JvwDl79NHyAVp_u0KgF3MVIP6RuDPa08qmAUW3wyHdM/edit#slide=id.g2b9763de157_0_75)
- Go to [Github repository](https://github.com/kathsherratt/r-for-research/tree/main)
  - Download the tutorials:
    - [R Markdown](tutorials/Rmarkdown-intro.Rmd)
    - [Github](tutorials/Github-intro.Rmd)

- Read the article that summarises the key recommendations for good (enough) practices in scientific computing
  - Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, Teal TK (2017) Good enough practices in scientific computing. PLoS Comput Biol 13(6): e1005510.
    - <https://doi.org/10.1371/journal.pcbi.1005510>
   
- Feedback welcome! Add your comments or suggestions for improving the workshop by posting in [this repository forum](https://github.com/kathsherratt/r-for-research/issues/).
  - [Open an Issue](https://github.com/kathsherratt/r-for-research/issues/new)

### Learning more

#### General resources

Most of these resources cover the key topics of the session (workflow, style guidance, R Markdown, and Git). If one doesn’t make sense to you, try another for a different explanation.

- Open Data Science with R: <https://carpentries-incubator.github.io/open-science-with-r>
- R for Statistical Programming: <https://smac-group.github.io/ds/>
- Efficient R: <https://csgillespie.github.io/efficientR/>
- Reproducible Data Science: <https://ecorepsci.github.io/reproducible-science/index.html>

#### Setting up RStudio Projects

- Creating efficient workflows: <https://csgillespie.github.io/efficientR/workflow.html>
- Managing dependencies with renv: <https://ecorepsci.github.io/reproducible-science/renv.html>

#### Coding

- Code style guides: <https://style.tidyverse.org>
- Writing functions: <https://r4ds.hadley.nz/functions>

#### Reporting and collaborating

- Rmarkdown:
  - <https://r4ds.had.co.nz/r-markdown.html>
  - <https://rmarkdown.rstudio.com/docs/articles/rmarkdown.html> 
- Github:
  - <https://rfortherestofus.com/2021/02/how-to-use-git-github-with-r> 
  - <https://happygitwithr.com>

#### Questions & resources

- Using R with large or confidential data sets 
  - This guide covers many useful practices, including the highly recommended `data.table` package:
    - <https://marketsplash.com/tutorials/r/how-to-handle-large-datasets-in-r>
  - `Arrow` is a great option for storing very large (roughly >8GB) datasets efficiently, and can be read into R (almost) as easily as a .csv file:
    - <https://r4ds.hadley.nz/arrow.html>
  - When using Github with large or confidential data sets, one strategy might be to use the `.gitignore` file to prevent Github from tracking or uploading a given data file:
    - <https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files>
- Writing reports with Rmarkdown
  - An example of a paper using Rmarkdown:
    - <https://github.com/epiforecasts/euro-hub-ensemble/tree/main/analysis>
  - Using `trackdown` for tracking changes with google docs:
    - <https://cran.r-project.org/web/packages/trackdown/vignettes/trackdown-workflow.html>
