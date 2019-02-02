# Note
A full report on the study can be found [here](https://docs.google.com/viewer?url=https://github.com/dexkluu/Features-affecting-animated-media-rating-and-rank/raw/master/R_Markdown_Output%2C%20Exploratory%20Analysis.pdf).

## Overview
Exploratory data analysis was performed to gain insights into whether customers prefer certain features of anime more than others.

## Tools Used

The analysis was done using R version 3.5.1 in a R markdown file. The output is a pdf after knitting. The libraries used were gridExtra, ggplot2, ggrepel, tidyverse, knitr, and kableExtra.

## Result
Based on the average scores for the features, it appeared that voice actors had the biggest range of rankings. However, for all the features the standard deviations were high for each value of the feature. This project focused only on exploratory data analysis, but if I had to make a guess, I would say that for this data, the differences would not be statistically significant. To improve the study, a larger and more spread out sample should be taken. Out of over 15,000 animes on myanimelist.net, only 950 of them were taken. Again, refer to the link in the notes for the tables and plots from the analysis.

## Replicate the analysis

To replicate my results, one could simply knit the R markdown file to pdf. The data is included in the repository. Ensure that all tools and libraries such as R markdown/knitting and the libraries mentioned in the "Tools Used" section are installed and running on your personal device.

## Author
* **Dexter Luu**
