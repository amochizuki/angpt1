---
title: "README"
output: 
  html_document:
    toc: true
    keep_md: true
---

***
# Test plots for Angpt1 project
This is a working document -- updates to code can be pushed in real time for easy viewing.








## UMAP plots 
### scGPT/LLM based annotations
![](README_files/figure-html/umap_scgpt-1.png)<!-- -->

### Annotations of Louvain clustering based on LLM labels.
![](README_files/figure-html/umap_labeled-1.png)<!-- -->

### UMAP plots demonstrating expression
Gfap is a marker used by [Filbin *et al*](https://doi.org/10.1038/s41588-022-01236-3) for AC-like tumor cells, Mog for oligodendrocytes.
![](README_files/figure-html/umap_plots-1.png)<!-- -->

##### Alternate color scheme
![](README_files/figure-html/umap_plots_alt-1.png)<!-- -->

***
## Boxplots
### All cell types

![](README_files/figure-html/boxplot-1.png)<!-- -->


### Limited to tumor cells only

![](README_files/figure-html/boxplot_limited-1.png)<!-- -->


### Adding points

![](README_files/figure-html/boxplot_limited_dots-1.png)<!-- -->

***
## Violin plots
### Tumor cells only
![](README_files/figure-html/violin-1.png)<!-- -->

### Adding points
![](README_files/figure-html/violin_points-1.png)<!-- -->

***
## Heatmap

![](README_files/figure-html/heatmap-1.png)<!-- -->

***
## Density plots
![](README_files/figure-html/density-1.png)<!-- -->

Built with R 4.4.2.
