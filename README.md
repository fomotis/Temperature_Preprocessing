Olusoji Oluwafemi Daniel
8 April 2019

# Flow Cytometer Files PreProcessing using R

It is important to note that this tutorial is written based on settings
on the `guavava` flow cytometer armed with the `lynCyte` software. Also
the settings on the cytometer is specially tuned for counting and
sorting cyanobacteria cells. While the tutorial might not be directly
applicable to other instruments and settings, the general idea is
applicable and the ensuring codes could be easily adapted.

## Needed Packages

``` r
#install.packages("flowCore")
#install.packages("flowDensity")
#Not yet available on CRAN
#devtools::install_github("fomotis/cyanoFilter")
```

## Contributors

  - Spaak Jurg
