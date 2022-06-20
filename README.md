# Introduction

These are the materials for *How to Create Publication-Ready Tables in R*, a short course taught at UseR! 2022 on Monday, June 20<sup>th</sup> 2022, 2:00 - 5:30pm CDT

# Abstract
This tutorial will teach attendees how to make fully reproducible, publication-ready tables for academic journals, public-facing talks and online displays. The strengths and weaknesses of popular table-making packages will be shown. After the guiding principles for table design are explained, attendees will learn how to build tables. The course will use a mixture of lecture and hands-on practice to produce beautiful tables that have already been published, and attendees will learn how to take these tables to the next level. Attendees will learn how to make both static and interactive tables during the tutorial topics, which include: quick descriptive statics with the table1 package; tables to support hypothesis testing with p-values using the gt with `gtsummary` packages; making complex tables which can be directly integrated using Microsoft Word with the `flextable` package; and making beautiful interactive tables with the `reactable` and `reactablefmtr` packages. The audience will also learn how to use the `rUM` package as a shortcut to building academic papers.

# Software 

If you can build packages on your machine, you can run the code below to download/install and or download/build packages.  If you don't know... you can use RStudio.Cloud.

## The Slides
The slides for this talk were created using the R `xaringan` package (version 0.24) with CSS help (ninjutsu.css, cssninja-scaffold.css, sydney.css).  Many thanks to: 

https://github.com/emitanaka/ninja-theme
https://github.com/matt-dray/ninja-scaffold 
https://github.com/garthtarr/sydney_xaringan


## The Content 
The code shown uses many packages.  To install all the parts try this:

```
if (!require('remotes')) install.packages('remotes')
remotes::install_cran(
  c(
    "conflicted", 
    "dplyr"
    "flextable", "flipbookr", "forcats",
    "gdtools", "gt", "gtable", "gtsummary", 
    "htmltools",
    "kable", "kableExtra", "knitr",
    "labelled",
    "medicaldata",
    "officer",
    "reactable", "reactablefmtr",
    "smd",
    "table1", "tidyr"
  )
)
remotes::install_github(
  c(
    "gadenbuie/xaringanExtra",
    "glin/reactable"
  )
)
```



# Instructors
**Raymond Balise**, PhD, is an award-winning lecturer, biostatistician working in the Miller School of Medicine at the University of Miami. His decades of experience studying cancer, health disparities, HIV and addiction have led to hundreds of peer-reviewed abstracts, posters, and papers.

**Lauren Nahodyl**, MS, is a biostatistician for the University of Miami Miller School of Medicine. Lauren’s research currently focuses on the areas of cardiovascular disease and cancer disparities.

**Anna Calderon**, BA, is a data analyst at the University of Miami with an interest in the intersection of healthcare research and machine learning. She has experience working in clinical research involving vulnerable populations and is currently involved in the application of machine learning to predict outcomes of substance use disorder treatments.

**Francisco Cardozo**, MS, is a data analyst and a PhD student at the University of Miami. He has been working on the evaluation of international preventive programs and developing tools to help communities quickly access the information they need to prevent alcohol use in adolescents.

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
