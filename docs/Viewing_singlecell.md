# View single cell data
## Cell embeddings
The center of single cell browser mainly displays the embedding with annotation, where each cell is a point. Different reduction methods, such as UMAP, tSNE or some other dimensionality, produce different cell clustering distributions.
![cell embeddings](/pictures/6_1.png)


## Marker feature visualization
 SGS Genome Browser provides multiple ways to display marker features such as marker gene, marker motif, marker peak. 

### Display of marker gene
In SGS single cell browser, users can explore single or multi marker genes through scatter plot, violin plot, boxplot or heatmap display methods.

The scatter plot of the marker gene mainly show the expression distribution of this gene in different cell clusters.
![cell embeddings](/pictures/6_2.png)

Violin plot or boxplot mainly shows the statistical distribution of the expression value of the marker gene in each cluster.
![Violin plot/boxplot](/pictures/6_3.png)

The heatmap shows the expression distribution of multiple marker genes in different cell groups. The cell group annotations and expression legends are displayed on the top and side of the heatmap, respectively.
![heatmap](/pictures/6_4.png)

### Display of marker peak
In addition to the display of marker genes, SGS genome browser visualizes the distribution of chromatin accessibility signals near the marker peaks of interest. By displaying the chromatin accessibility peaks of multiple marker peaks at the same time, it is convenient for users to perform comparative analysis.
![marker peak](/pictures/6_5.png)

### Display of marker motif
For the marker motif, in addition to providing conventional displays such as scatter plots, violin plots etc. SGS genome browser also draws the motif logo.
![marker motif](/pictures/6_6.png)

## scRNAseq track visualization
In order to facilitate users to view the structure of the marker gene of interest and obtain the expression of the gene in different cell groups, SGS genome browser displays the median expression of the gene in each cell groups through bar graphs at the location of a gene. Each bar represents a cell or tissue type. The height of the bar graph on the genome is the median expression level. Users can gain the expression scatter plot in the single cell browser by click on the gene bar track in the genome browser.
![scRNAseq](/pictures/6_7.png)

## scATACseq track visualization
For single-cell atac data, the SGS browser mainly displays the following three pieces of information:
(1) Distribution of chromatin accessibility in different cell groups; (2) Marker peaks obtained by analysis; (3) Correlation lines of peak-peak/peak-gene obtained by co-accessibility analysis. 
![scATAC](/pictures/6_8.png)

