# User interface
## Main Window
The following figure shows the main interface of SGS browser.
![the mian interface of SGS browser](/pictures/4_1.2.png)





## Settings 
The Settings menu controls global settings of the browser.
### Color Theme
Color Theme used to setting the software interface theme color.
![Color Theme](/pictures/4_2.png)

### Theme Mode
We offered two theme mode:Light mode, Dark mode.
![Theme Mode](/pictures/4_3.png)

### Data Cache and Setting Cache
Data cache and setting cache used to clear data and set cache respectively.
![Data Cache and Setting Cache](/pictures/4_4.png)



## Server and data management
Users can deploy SGS services through the shortcut option <b><font color=#3A5FCD>New SGS server</font></b> or <b><font color=#3A5FCD>Home</font></b> --> <b><font color=#3A5FCD>New SGS server</font></b>. The detailed steps of deployment, please refer to:<a href="http://127.0.0.1:8000/installation/" target="_blank">Installation and deploy</a> .

### Server list
The server list menu bar mainly displays the currently added SGS service url. By clicking the edit button option (2), users can change the url address and name; by clicking URL setting (2), the URL can be deleted or connected to the relevant data management center; finally, users can also able to re-add new SGS service URLs.

![Server managment](/pictures/4_5.1.png)

### Database connection
Clicking the data management button, we will enter the database longin interface. By clicking "Log to new server", we can switch the service IP and enter the data list interface to delete or add track data.
![Data Cache and Setting Cache](/pictures/4_5.png)

## Adding species
To add a new species, you need to click the "add species" botton. Then, You should fill in the corresponding species name and description information, and choose a fasta file in the data dir.
![Adding species](/pictures/4_6.png)



## Adding tracks
SGS support three types of tracks, namely Genome、Transcript(single cell transcipt) and ATAC(single cell atac). To add tracks, you first need to choose track types, then load files. Users can add single file or multi files at the same time.
![Adding tracks](/pictures/4_7.png)


The following file formats are supported:

| Formats | GFF | VCF | BAM | BIGWIG | BED | melthyC | biginteract | BedGraph | Longrange | Seurat object | Signac object |
| :----: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
| Track types | Genome | Genome | Genome | Genome | Genome | Genome | Genome | Genome | Genome | Transcript | ATAC |



## Track management
### Track list
Track list mainly display added tracks. Users can search track by name(1)、select track、 sort tracks by track data formats(2) or change track orders by dragging track order icon(3).
![Track list](/pictures/4_8.png)

### Track theme
Users can import or ceate new track feature style(1). Track theme setting allows user to customize track feature display shape, color, height and font size for different tracks(2-3).
![Track theme](/pictures/4_9.png)

### Track menu
Users can access track-specific function by using the track menu, which is accessible from the track selecter itself. Some functions are track-specific, but more function are basic options like <b><font color=#3A5FCD>Track Height</font></b>, <b><font color=#3A5FCD>Track Color</font></b>, <b><font color=#3A5FCD>Rename Track</font></b> are available from the track menu on the track selector.
![Track theme](/pictures/4_10.png)

### Track information
Users can view the detailed description of the feature on the right by clicking the track feature.
![Track information](/pictures/4_11.png)



## Browser your data
The top navigation menu controls most of the browser functionality. From left to right are compare mode, species and assembly information, genomic region locator, zoom in/out tools, min/max scale, region selection, undo/redo and share session:
![Top memu bar](/pictures/4_11.1.png)

### Species list
User can view omics data added in different species by clicking on species selection button.
![Top memu bar](/pictures/4_11.1.2.png)

### Track view operations
#### Move/Zoom/minsale/maxscale tools
User can change the current region by draging the mouse right or left or by click the left or right <b><font color=#3A5FCD>move</font></b> button. <b><font color=#3A5FCD>Zoom</font></b> mode allows the user to zoom in or zoom out on a specific region within the cuurent view using the mouse.  Besides, <b><font color=#3A5FCD>Min/Max scale</font></b> mode allows user to change the view to min or max zoom scale.

![Move/Zoom tools](/pictures/4_11.1.3.png)

#### Region higlight tools
Region higlight function allows user to higlight the region they select.

![Region higlight](/pictures/4_11.1.4.png)

#### Redo/Undo tools
For instance if you accidently moved to another region and forgot what you were looking at before you can click the <b><font color=#3A5FCD>Undo</font></b> button to go back. Clicking the <b><font color=#3A5FCD>Redo</font></b> button allows you to go forward to the step before you clicked <b><font color=#3A5FCD>Undo</font></b>.

![Redo/Undo tools](/pictures/4_11.1.5.png)

#### Search tools
##### Search by region
Users can find intervals of interest by entering genomic coordinates in format of <b><font color=#3A5FCD>ctgA:23364-25651</font></b>.

![Search by region](/pictures/4_11.1.6.png)

##### Search by name
Enter the gene name, you can quickly jump to the position of the gene.

![Search by name](/pictures/4_11.1.7.png)




## Sharing session
SGS browser allows users to share session with other users. Just clicking on the share session botton in the sidebar or the top navigation menu, you can copy and send the URL to other user.
![Sharing session](/pictures/4_7.1.png)



## The compare mode
SGS provides the compare function to compare the differences in the distribution of genomic data on different chromosomes of the same species.
![Compare mode](/pictures/4_11.1.1.png)

Users can switch to a different chromosome for comparison via the position manipulation box at the top or botton. By hovering over a chromosome, users can zoom in/zoom out the current visualization area through the scroll wheel, and switch the chromosome area by dragging left and right.



## Single cell browser
### Single cell data list
Clicking on the single cell browser, we can view the single cell datasets that have been added so far, and by selecting one of the datasets, we can view them in the single cell browser.
![Single cell data list](/pictures/4_12.png)

### Single cell browser interface
The single cell browser main display the cell annotated scatterplot derived from UMAP, tSNE, or some other dimensionality reduction method. The image below highlights some of the main features of this core visualization:

![Single cell data list](/pictures/4_13.png)

The toolbox is on the top of the single cellbrowser window and contains tools that perform the functions  list in the table below:

| Icon | Function Description |
| :----: | :------: |
| ![save picture](/pictures/4_13.1.png) | Used to save the currently single cell view as a jpg image |
| ![reset view](/pictures/4_13.2.png) | Used to reset the single-cell view to its initial state |
| ![change matrix](/pictures/4_13.3.png) | When uploading multiple types of matrix files, it is used to switch between different matrixes |
| ![change reduction](/pictures/4_13.3.1.png) | Used to change cell embedding, tSNE/UMAP |
| ![change color](/pictures/4_13.4.png) | Used to change the cell cluster color according to different cell annotation methods |
| ![change label](/pictures/4_13.5.png) | Used to change cell annotation label |
| ![show legend](/pictures/4_13.6.png) | Used to display the currently viewed cell annotation legend |
| ![show axis](/pictures/4_13.7.png) | Used to display cell reduction coordinate system |
| ![dot setting](/pictures/4_13.8.png) | Used to adjust the size of the points in the cluster graph |
| ![rstudio server](/pictures/4_13.9.png) | Used to enter Rstudio server |
| ![change layout](/pictures/4_13.10.png) | It is used to change the layout of the single-cell window, mainly providing three layout modes: left, right and bottom |
| ![marker table](/pictures/4_13.11.png) | View marker table |

Users can view different matrix such as: peak matrix, motif matrix or gene exp matrix just by clicking on the ![change matrix](/pictures/4_13.3.png) boutton. Besides, when multi reduction data have upload, users can switch to different reduction plots with ![change reduction](/pictures/4_13.3.1.png) button. Users will gain the cell anotation of the cell cluster when they use the ![change label](/pictures/4_13.5.png) option. Fourthermore, with the opening of ![show legend](/pictures/4_13.6.png) option, users can also change the color of the cell cluster or hide the cell clster by clikcing the color box or cluster name respectively.


### Marker table
We provide graphs and charts to display single-cell markers.
![Marker table](/pictures/4_14.png)

<b><font color=#3A5FCD>(1)</font></b> By clicking on the marker gene, the single-cell browser displays the expression of the marker in different cell types, and if the genome-related data such as gff is uploaded, the genome browser will quickly jump to the gene position.
![Marker table](/pictures/4_15.png)

<b><font color=#3A5FCD>(2)</font></b> By dragging left and right to view the complete marker table information, and view more markers by pulling up the table or clicking the page turning option; (3) By clicking the graphics icon, you can view the marker gene expression scatterplot.
![Marker table](/pictures/4_16.png)


### scMultiCompare
It is critical to view multiple markers simultaneously in  single-cell researches. By selecting multiple markers in the single-cell marker table, click scMultiCompare to enter the single-cell multi-marker compare module.
![scMultiCompare](/pictures/4_17.png)


+ by cliking on <b><font color=#3A5FCD>change view mode</font></b>, switch the horizontal or vertical graphics display mode.
+ by cliking on <b><font color=#3A5FCD>change view type</font></b>, you can switch between multiple marker display modes, mainly: compare and heatmap.
+ <b><font color=#3A5FCD>show label</font></b>: used to display the plot type label.
+ by cliking on <b><font color=#3A5FCD>choose plot type</font></b>, users can choose the drawing type, mainly including cell.  clustering plot, box plot, violin plot, Motif Logo maps, peak coverage plot.

### Rstudio Server
Users can load the single cell analysis object directly from R into SGS single-cell browser by clicking the 
![Rstudio Server](/pictures/4_18.1.png) button. For detailed manual, please refer to this link：<a href="http://127.0.0.1:8000/R_server/" target="_blank">Cudie of R server</a>



