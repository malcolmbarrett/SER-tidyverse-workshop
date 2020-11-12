# SER Workshop: Data manipulation, visualization, and reproducible documents with R and the Tidyverse

## Thursday, Nov 19, 2020, 9am – 1pm PT (12pm - 4pm ET)

Recent developments by the R community have revolutionized the data analysis pipeline in R, from manipulating and visualizing data to communicating results. Our workshop will provide hands-on training in tools from the tidyverse ecosystem, using real epidemiologic data. In the first section, we will teach data manipulation with dplyr, a package that makes data cleaning easy, flexible, and enjoyable. In the next section, we will teach data visualization with ggplot2, the most popular plotting package in R, with a focus on creating publication-quality plots. We will then put these tools together to make reproducible documents. Using R Markdown, we will weave code and text together and learn to write papers and reports, exported to PDF, Word, or HTML, entirely in R. This workflow easily propagates upstream changes to data or analyses throughout a document and eliminates copy and paste errors. Together, these tools form a data analysis pipeline for reproducible, publication-ready work.

## Materials setup

* Make sure you have [R](https://cloud.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/download/#download) installed (see the [introductory PDF](https://github.com/malcolmbarrett/SER-tidyverse-2020/raw/master/slides/00_Intro-to-R.pdf)). Additionally, make sure you have the tidyverse and gapminder packages installed:

```r
install.packages(c("tidyverse", "gapminder"))
```

* Set up an account at [RStudio Cloud](http://rstudio.cloud/). We'll have a free cloud version R and RStudio available with all of the workshop materials included in case you have any issues with your local installation!
* Download these materials locally using the usethis package:

```r
install.packages("usethis")
usethis::use_course("malcolmbarrett/SER-tidyverse-2020")
```

usethis will open the files right in RStudio. To open it in the future, open the `SER-tidyverse-2020.Rproj` file by double-clicking it or, in RStudio, navigate to File > Open Project.

## Agenda (in Pacific Time)

* 8:50-9:00: Zoom room open
* 9:00-10:00: Data manipulation using dplyr (Malcolm), [Slides](https://ser-tidyverse-2020.netlify.app/dplyr_5verbs/dplyr_5verbs.html)
* 10:00-11:00: Data visualization using ggplot2 (Corinne), [Slides](https://musing-benz-8f7c86.netlify.app/02_slides.html)
* 11:00-11:15: Break
* 11:15-12:15: Data visualization team exercise (Corinne and Malcolm), [Slides](https://musing-benz-8f7c86.netlify.app/03_slides.html)
* 12:15-1:00: Reproducible reports and manuscripts using R markdown (Malcolm), [Slides](https://ser-tidyverse-2020.netlify.app/rmarkdown_basics/rmarkdown_basics.html)
