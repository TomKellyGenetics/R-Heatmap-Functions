R-Heatmap-Functions
===================

Altered by Mik Black and Tom Kelly at the University of Otago

Modifications to the R function heatmap.2 {gplots}

requires R packages gplots and gtools

heatmap.mik: enable multiple colorbars for ColSideColors with rbind, rownames are labels

heatmap.mik2: enable multiple colorbars for ColSideColors with rbind, rownames are labels, and enable multiple colorbars for RowSideColors with cbind, colnames are labels


heatmap.mik.mod: heatmap.mik with column reordering supressed if a dendrogram is given for Colv, allows manual reordering of input matrix, dendrogram, and ColSideColors for custom dendrograms

heatmap.mik.mod2: functionality of heatmap.mik2 with supression of column reordering as above
