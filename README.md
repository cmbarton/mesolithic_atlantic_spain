# SPD data and analysis script for paper "The Mesolithic of Atlantic Coastal Spain" by GA Clark & CM Barton

Copyright (c). C Michael Barton and Geoffrey A Clark, Arizona State University 2021. 

This package includes the original data and analysis scripts needed to reproduce the summed probability distribution analyses of prehistoric demography presented in figures 18-22 and text of the following published paper:

Clark, Geoffrey A and C Michael Barton (2021). The Mesolithic of Atlantic Coastal Spain – a Comparison with the Middle Ebro Basin. *Comptes Rendus Palevol*.

Included in this package is:

1. A csv database of radiocarbon dates for the Epipaleolithic though Mesolithic of Atlantic Coastal Spain, from Galicia through the Basque Country, and the upper Rio Ebro valley (NIberia_all.csv)
2. RMarkdown script to carry out sum probability distribution (SPD) analyses discussed in the paper (clark-barton2022_SPD-figures.Rmd).
3. An HTML file showing example output from running the Rmd with the csv data file. 

Analyses were carried out using R ver. 4.1.0 and RStudio 1.4

To reproduce the analysis, make sure that the csv and Rmd files are in the same folder on your computer. Launch RStudio and set the working directory to the folder containing the csv and Red files (use RStudio functions or the R command setwd()).

You should then be able to *knit* the results to an output format of your choice.

If you have questions you can (currently) reach the lead author of this file at michael.barton@asu.edu. 


