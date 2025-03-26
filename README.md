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


### UMAP of clusters plus UMAP of tumors
![](README_files/figure-html/umap_labeled-1.png)<!-- -->

### UMAP of clusters by tumor type - supplemental plus frequency plot
![](README_files/figure-html/umap_by_tumor-1.png)<!-- -->

### UMAP plots demonstrating expression
Gfap is a marker used by [Filbin *et al*](https://doi.org/10.1038/s41588-022-01236-3) for AC-like tumor cells, Mog for oligodendrocytes.


##### Alternate color scheme - use FeaturePlot color scheme
![](README_files/figure-html/umap_plots_alt-1.png)<!-- -->

#### FeaturePlot style
![](README_files/figure-html/feature_plot-1.png)<!-- -->

***
## Bar plots 
### Cell type frequency
![](README_files/figure-html/bar_graph-1.png)<!-- -->

***
## Boxplots
### All cell types




### Limited to tumor cells only




### Adding points

![](README_files/figure-html/boxplot_limited_dots-1.png)<!-- -->

***
## Violin plots
### All cells


### Tumor cells only


### Adding points - split into tumor/non-tumor
![](README_files/figure-html/violin_points-1.png)<!-- -->

***
## Heatmap
### By cell



### By cluster
#### Scaled - restrict to just tumor clusters for main figure; can have all for supplemental
![](README_files/figure-html/heatmap_mean_scaled-1.png)<!-- -->

#### Midpoint 0
![](README_files/figure-html/heatmap_mean-1.png)<!-- -->

***
## Density plots


Built with R 4.4.3.
