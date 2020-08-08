# mapping-options
This repository contains the files for a presentation I gave at the HMSC-useR group meeting on 10 February 2015 that provided an overview of R packages that can be used to create maps. The presentation can be viewed in the *RPubs* page of the  [HMSC_useR group](https://rpubs.com/hmsc_useR/59430).

The source code is contained in the R Markdown file "mapping_hmsc_useR.Rmd". To use it, you need the `knitr` and `markdown` packages installed in RStudio. Other required packages specific to the presentation are documented in the source file.

To build the presentation in R, run `knit2html("mapping_hmsc_useR.Rmd")`, or use the `knit_HTML` button in RStudio.

Note that the contents of the presentation are rather outdated, as there has been much progress, and more and better options for mapping in R have come out since. For example, take a look at the slide presentation by [Olivier Gimenez](https://oliviergimenez.github.io/) ["Introduction to GIS and mapping in R using the `sf` package"](https://github.com/oliviergimenez/intro_spatialR).
