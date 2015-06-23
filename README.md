R-Heatmap-Functions
===================

Altered by Mik Black and Tom Kelly at the University of Otago

Modifications to the R function `heatmap.2 {gplots}`

requires R packages `gplots` and `gtools`

`heatmap.mik`: enable multiple colorbars for _ColSideColors_ with `rbind`, rownames are labels

`heatmap.mik2`: enable multiple colorbars for _ColSideColors_ with `rbind`, rownames are labels, and enable multiple colorbars for _RowSideColors_ with `cbind`, colnames are labels


`heatmap.mik.mod`: `heatmap.mik` with column reordering supressed if a dendrogram is given for Colv, allows manual reordering of input matrix, dendrogram, and _ColSideColors_ for custom dendrograms

`heatmap.mik.mod2`: functionality of `heatmap.mik2` with supression of column reordering as above
`heatmap.mik.mod2x`: functionality of `heatmap.mik2` with supression of column (and row) reordering as above

`heatmap.mik.tk`: `heatmap.mik` (multiple colour bars enabled) with label editing restored from `heatmap.2`

`heatmap.mik.tk2`: `heatmap.mik2` (multiple and row colour bars enabled) with label editing restored from `heatmap.2`

Citation: Gregory R. Warnes, Ben Bolker, Lodewijk Bonebakker, Robert Gentleman,
  Wolfgang Huber Andy Liaw, Thomas Lumley, Martin Maechler, Arni
  Magnusson, Steffen Moeller, Marc Schwartz and Bill Venables (2015).
  gplots: Various R Programming Tools for Plotting Data. R package
  version 2.17.0. http://CRAN.R-project.org/package=gplots
