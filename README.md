## Overview

Single-cell and spatial gene expression data are very high-dimensional, which makes dimension reduction a crucial step in the analysis pipeline. However, many popular examples of dimension reduction methods, such as Principal Component Analysis (PCA), ignore the purpose of a dimension reduction procedure, which is to assist in a specific downstream analysis. wSIR is a supervised dimension reduction method, which makes use of cells' spatial locations to compute a spatially-informed low-dimensional embedding.

## Description

In this workshop, we will introduce the wSIR method for supervised dimension reduction of spatial transcriptomics and single-cell gene expression data. We will explain the method, and go through some example analyses to demonstrate how the method is applied. We will also perform some simple analyses to demonstrate its utility. 

### Pre-requisites

It is expected that students will have:

- basic knowledge of R syntax, and
- familiarity with single-cell and spatial transcriptomics data.

### Time outline

The expected timing of the workshop:

| Activity                                      | Time |
|-----------------------------------------------|------|
| wSIR method overview                          | 20m  |
| wSIR application: interpretability            | 15m  |
| wSIR application: improved modelling accuracy | 15m  |

### Learning objectives

- Understand the wSIR method.
- Use wSIR to project new single-cell gene expression data into a spatially-informed low-dimensional space.
- Examine the wSIR loadings to derive biological insight
- Use wSIR to improve accuracy in downstream analysis