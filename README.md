# BUILD
FROM jupyter/minimal-notebook

#R-Base 
  version 3.3.1

#R-packages
    r-base=3.3.1 1
    r-irkernel=0.7
    r-plyr=1.8
    r-devtools=1.11
    r-dplyr=0.4
    r-ggplot2=2.1
    r-tidyr=0.5
    r-shiny=0.13
    r-rmarkdown=0.9
    r-forecast=7.1
    r-stringr=1.0
    r-rsqlite=1.0
    r-reshape2=1.4
    r-nycflights13=0.2
    r-caret=6.0
    r-rcurl=1.95
    r-crayon=1.3
    r-randomforest=4.6
    
#Bioconductor packages

    annotate
    limma
    affy
    GEOquery
    SVGAnnotation
    affxparser
    simpleaffy
    hgu133a.db
    hgu133a2.db
    hgu133plus2.db
    hugene10sttranscriptcluster.db
    oligo
    frma
    hgu133afrmavecs
    hgu133plus2frmavecs
    hgu133plus2cdr
    hgu133acdf
    hugene10stv1cdf
    arrayQualityMetrics
    genefilter
    pathifier
    
    
    ## Installation

The image is built automatically by the docker automated build system. To get
the latest version just pull it in docker.

```bash
docker pull fmunoz/jupyter_r_microarrays
```
