# Downloading Data from TCGA

Code to download data is in `index.Rmd`. Note that the package `TCGAbiolinks` needs to be installed for data download. 

Data needs to be re-queried and loaded for every new R session; however, data only needs to be downloaded once. If this is your first time downloading this data, please uncomment the line `GDCDownload`. 