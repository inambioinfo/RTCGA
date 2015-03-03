# RTCGA


<h5> Installing RTCGA package: </h5>
To get started, install the latest version of **RTCGA** from Bioconductor:
```{Ruby}
# not there yet
```
or use:
```{Ruby}
if (!require(devtools)) {
    install.packages("devtools")
    require(devtools)
}
install_github("MarcinKosinski/RTCGA")
```
Make sure you have [rtools](http://cran.r-project.org/bin/windows/Rtools/) installed on your computer.

<h5> The list of available functions: </h5>
```{Ruby}
help(package="RTCGA")
```
<h4> The list of use-cases: </h4>

TODO.

# Mission

The Cancer Genome Atlas (TCGA) Data Portal provides a platform for researchers to search, download, and analyze data sets generated by TCGA. It contains clinical information, genomic characterization data, and high level sequence analysis of the tumor genomes[1]. The key is to understand genomics to improve cancer care. RTCGA package offers download and integration of the variety and volume of TCGA data using patient barcode key, what enables easier data possession. This may have an benefcial infuence on impact on development of science and improvement of patients' treatment. RTCGA is an open-source R package, available to download from Bioconductor[2]. Furthermore, RTCGA package transforms TCGA data to form which is convenient to use in R statistical package. Those data transformations can be a part of statistical analysis pipeline which can be more reproducible with RTCGA
