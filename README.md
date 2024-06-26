# TPWshiny: an interactive R/Shiny app to explore cell line transcriptional responses to anti-cancer drugs
download the R code TPWshiny.R (107 KB) (requires R 4.3 or above);
install the 'groundhog' package, used by the source code to automatically download any missing R package TPWshiny requires;
to launch: set the working directory as the directory where you saved TPWshiny.R (using the command "setwd") and run the app with the command shiny::runApp('TPWshiny.R');
alternatively, in RStudio, you can simply click the "> Run App" button located at the top right corner of the RStudio interface.

TPWshiny is a robust, independent visualization tool for comprehensive genome-wide profiling of NCI-60 human cancer cell lines' responses to 15 distinct anticancer drugs across multiple time intervals. This data is sourced from the NCI Transcriptional Pharmacodynamics Workbench (NCI TPW), which compiles measured transcriptional responses to anticancer agents. While the NCI TPW data is accessible through a web interface with limited interactivity, TPWshiny, designed as an R Shiny application, enhances data exploration. It offers an intuitive interface that enhances comprehension of tumor cell characteristics across nine different tissue types, aiding researchers in their investigations. The data is presented through interactive scatter plots, heat maps, time series, and Venn diagrams, allowing users to query information based on drug concentration, time points, genes, and tissue types, with the option to download the data for further analysis.
TPWshiny documentation and additional information can be found on https://brb.nci.nih.gov/TPWshiny/

TPWshiny has been deployed on a shinyapp server.
You can access it directly at https://ncibrp.shinyapps.io/TPWshiny1/</br></br>
**If you use this tool for your analysis, please cite:** Zhang P, Palmisano A, Kumar R, Li MC, Doroshow JH, Zhao Y. TPWshiny: an interactive R/Shiny app to explore cell line transcriptional responses to anti-cancer drugs. Bioinformatics. 2022 Jan 3;38(2):570-572. doi: 10.1093/bioinformatics/btab619. PMID: 34450618; PMCID: PMC10060698.
