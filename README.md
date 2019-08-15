# DIscBIO:a user-friendly pipeline for biomarker discovery in single-cell transcriptomics


We present DIscBIO, an open, multi-algorithmic pipeline for easy, fast and efficient analysis of cellular sub-populations and the molecular signatures that characterize them. The pipeline consists of four successive steps: data pre-processing, cellular clustering with pseudo-temporal ordering, defining differential expressed genes and biomarker identification. All the steps are integrated into an interactive notebook where comprehensive explanatory text, code, output data and figures are displayed in a coherent and sequential narrative. Advanced users can fully personalise DIscBIO with new algorithms and outputs. We also provide a user-friendly, cloud version of the notebook that allows non-programmers to efficiently go from raw scRNAseq data to biomarker discovery without the need of downloading any software or packages used in the pipeline.

![DiscBIO.png](https://raw.githubusercontent.com/username/projectname/branch/path/to/DiscBIO.png)

Try it with Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SystemsBiologist/PSCAN/master)



In case the user would like to run the notebook using Jupyter, this code should be run first:
source("https://bioconductor.org/biocLite.R")
biocLite(c("pheatmap","MASS","cluster","mclust","flexmix","lattice","fpc",
                "amap", "RColorBrewer","locfit","TSCAN","genefilter","statmod",
                "ggplot2","gplots","DESeq2","matrixStats","robustbase","philentropy",
                "igraph","boot","biomaRt","tidyr","calibrate","partykit","RWeka",
                "rpart","rpart.plot","imager","png","NetIndices","httr","jsonlite","tidyverse",
                "samr","tidyverse"))
