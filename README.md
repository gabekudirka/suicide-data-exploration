# suicide-data-exploration
Built to aid researchers visualize factors in suicide death. CS 6955 - University of Utah

The wrangle data file takes in the original dataset given to us and processes it into 
different subpopulations, encoding categorical data, filling in missing values, and transforming 
phecode columns.

The clustering files take in the processed data, perform various clustering techniques and
outputs their visualizations.

The dim_reduce file takes in the processed data, performs PCA and UMAP techniques and outputs
their visualizations.

The mapper applies the mapper algorithm to the processed data and outputs their visualizations
to html files.

All of the processed data files are in the data folder.