# A Beginner's Guide to Analyzing scRNA-seq

-   **When**: 10-12 pm Feb 25th & 27th, March 4th and 6th
-   **Where**: TMEC 333 Conference Room

## Prework
-   [R-basics](https://github.com/hms-immunology/scRNA-workshop/blob/main/prework/R-basics.R)

-   [Data Wrangling](https://github.com/hms-immunology/scRNA-workshop/blob/main/prework/data-wrangle-viz-practice.R)

## Day 1: Tuesday Feb 25th

-   [Introduction to R/Rstudio](https://github.com/hms-immunology/intro-R-workshop)
    -   How to navigate Rstudio
    -   Fundamentals and data wrangling in R
-   [Introduction to Seurat](https://github.com/hms-immunology/scRNA-workshop/blob/main/day-1/1-Introduction.pdf)
    -   Working with a Seurat object
-   [Basic sc-RNAseq workflow](https://github.com/hms-immunology/scRNA-workshop/blob/main/day-2/1-Basic-scRNAseq-Analysis-Workflow.pdf)
    -   Main steps for scRNAseq workflow
    -   Intuition behind each step

## Day 2: Thursday Feb 27th

-   [Quality Control](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-2/2-QC.html) 
    -   How to carry out QC analysis
    -   What parameters do we need to look at and how to interpret them
    -   Computing doublet scores
    -   Tips and tricks during the QC process
-   [PCA, Integration & KNN graphs](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-3/1-PCA_Harmony_kNN.html)[
    -   Brief overview on PCA and how to use it for sc-RNAseq
    -   KNN-graph representation of the data
    -   Correcting batch effects with Harmony
-   [Suppl Normalization & HVG selection](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-2/Suppl-norm-hvg.html)
    -   Why and how to normalize sc-RNAseq data
    -   Why and how to select highly variable genes

## Day 3: Tuesday March 4th

-   [Clustering](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-3/2-Clustering.html) 
    -   How to cluster sc-RNAseq data
    -   What algorithms can we use
    -   How to assess if a clustering resolution is good
-   [Differential Gene Expression & Level 1 Annotation](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-4/1-dge-annot-level1.html) 
    -   How to compute differentially expressed genes between clusters
    -   How to evaluate differential expression statistics
    -   Reference-based cell type annotation
    -   Manual cell type annotation
-   [Suppl Subclustering & Level 2 Annotation](http://htmlpreview.github.io/?https://github.com/hms-immunology/scRNA-workshop/blob/main/day-4/2-Subclustering-level2.html) 
    -   What does level 2 annotation mean and why we need it
    -   How to iteratively annotate a dataset

## Day 4: Thursday March 6th

-   [Gene Signatures](http://htmlpreview.github.io/?)
-   [Compositional Analysis](http://htmlpreview.github.io/?)

## Resources

### Best practices
-   [Orchestrating Single-Cell Analysis with Bioconductor - R](https://bioconductor.org/books/3.17/OSCA/index.html#)
-   [Single-cell best practices - Python](https://www.sc-best-practices.org/preamble.html)

### Videos with basics
-   [MPG Primer: scRNA-seq analyses: challenges, opportunities, and best practices, Part 1 (2020)](https://www.youtube.com/watch?v=q--Hr9ZOpH4&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [MPG Primer: scRNA-seq analyses: challenges, opportunities, and best practices, Part 2 (2020)](https://www.youtube.com/watch?v=qUjBmCQoKhU&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [MPG Primer: Introduction to scRNAseq workflow (2025)](https://www.youtube.com/watch?v=hbLNA635Mzs&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [Sanbomics](https://www.youtube.com/@sanbomics)
-   [Bioinformagician](https://www.youtube.com/@Bioinformagician)
