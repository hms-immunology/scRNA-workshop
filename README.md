# A Beginner's Guide to Analyzing scRNA-seq

-   **When**: 10-12 pm Feb 25th & 27th, March 4th and 6th
-   **Where**: TMEC 333 Conference Room

## Prework
-   [R-basics]()

-   [Data Wrangling]()

## Day 1: Tuesday Feb 25th

-   [Introduction to R/Rstudio/Seurat](https://github.com/CellDiscoveryNetwork/workshops/tree/main/beginners-guide-to-analyzing-scRNAseq/prework)
    -   How to navigate Rstudio
    -   Fundamentals and data wrangling in R
-   [Introduction to Seurat]()
    -   Working with a Seurat object

## Day 2: Thursday Feb 27th

-   [Basic sc-RNAseq workflow](https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-1/The%20Basic%20scRNAseq%20Analysis%20Workflow.pdf)
    -   Main steps for scRNAseq workflow
    -   Intuition behind each step
-   [TBD Normalization & HVG selection](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-1/3-norm-hvg.html)
    -   Why and how to normalize sc-RNAseq data
    -   Why and how to select highly variable genes
-   [Quality Control](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-2/5-QC.html) 
    -   How to carry out QC analysis
    -   What parameters do we need to look at and how to interpret them
    -   Computing doublet scores
    -   Tips and tricks during the QC process

## Day 3: Tuesday March 4th

-   [PCA, Integration & KNN graphs](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-1/4-PCA_Harmony_kNN.html)[
    -   Brief overview on PCA and how to use it for sc-RNAseq
    -   KNN-graph representation of the data
    -   Correcting batch effects with Harmony
-   [Clustering](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-2/6-Clustering.html) 
    -   How to cluster sc-RNAseq data
    -   What algorithms can we use
    -   How to assess if a clustering resolution is good

## Day 4: Thursday March 6th

-   [Differential Gene Expression & Level 1 Annotation](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-2/7-dge-annotlvl1.html) 
    -   How to compute differentially expressed genes between clusters
    -   How to evaluate differential expression statistics
    -   Reference-based cell type annotation
    -   Manual cell type annotation
-   [TBD Subclustering & Level 2 Annotation](http://htmlpreview.github.io/?https://github.com/CellDiscoveryNetwork/workshops/blob/main/beginners-guide-to-analyzing-scRNAseq/day-2/8-Subclustering.html) 
    -   What does level 2 annotation mean and why we need it
    -   How to iteratively annotate a dataset

## Resources

### Best practices
-   [Orchestrating Single-Cell Analysis with Bioconductor - R](https://bioconductor.org/books/3.17/OSCA/index.html#)
-   [Single-cell best practices - Python](https://www.sc-best-practices.org/preamble.html)

### Videos
-   [MPG Primer: scRNA-seq analyses: challenges, opportunities, and best practices, Part 1 (2020)](https://www.youtube.com/watch?v=q--Hr9ZOpH4&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [MPG Primer: scRNA-seq analyses: challenges, opportunities, and best practices, Part 2 (2020)](https://www.youtube.com/watch?v=qUjBmCQoKhU&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [MPG Primer: Introduction to scRNAseq workflow (2025)](https://www.youtube.com/watch?v=hbLNA635Mzs&pp=ygUUTVBHIHByaW1lciBzY1JOQSBzZXE%3D)
-   [Sanbomics](https://www.youtube.com/@sanbomics)
-   [Bioinformagician](https://www.youtube.com/@Bioinformagician)
