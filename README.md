# Workshop Materials
### Data Visualization for Environmental Epidemiology with ggplot2: Mastering Presentation-Grade Figures

## Instructors
- Alexandra E. Larsen<sup>1</sup>, PhD (alexandra.larsen@duke.edu)
- Alison K. Krajewski<sup>2</sup>, PhD (krajewski.alison@epa.gov)
- Lauren H. Wyatt<sup>2</sup>, PhD (wyatt.lauren@epa.gov)

<sup>1</sup> Department of Biostatistics and Bioinformatics, Duke University School of Medicine, Durham, NC, USA

<sup>2</sup> Center for Public Health and Environmental Assessment, United States Environmental Protection Agency (US EPA), Durham, NC, USA

## Background & Significance
Data visualization is critical to conveying new findings in environmental health and is a vital part of advancing the field of environmental epidemiology around the globe. There are a variety of options for creating figures with licensed software, but data visualization packages like ggplot2 in the open-source software, R, are easily accessible and economical alternatives that can produce high quality and journal-ready figures. The syntax of ggplot2 is challenging to learn, so this workshop aims to allow participants to become comfortable with the syntax of ggplot2, create elegant, complex figures, and be able to apply the skills learned to their own research projects. 

## Content
This session will begin with an introduction to the ggplot2 package and supporting packages with live-coding and interactive examples using R studio. We will cover general practices for manipulating data structures and data formatting for creating ggplots. We will spend the majority of the workshop introducing examples of various plots that are frequently used in environmental epidemiology, focusing on the following aspects: 
* Adding confidence intervals to point estimates; 
* Manipulating background, axis, titles, legends, colors, themes; 
* Creating maps;
* Saving and exporting high quality figures for presentations and publications. 

We expect that participants will have some experience in statistical programming. No prior experience with ggplot is necessary, but this workshop is not meant to be an introduction to R. A brief guide to installing R, RStudio, and packages can be found [here](../master/Setup/Installation_guide_R.docx) and R version and packages to be installed prior to the workshop [here](../master/Setup/Workshop_R_packages.md).

## Pre-course preparation
- Install or update **R program** (R version 3.5.2) and **RStudio** (1.2.5033). A brief guide to installing R, RStudio, and packages can be found [here](../master/Setup/Installation_guide_R.docx) and R version and packages to be installed prior to the workshop [here](../master/Setup/Workshop_R_packages.md).
- Install the necessary R packages:
   - ggplot2, datasets, mlbench, data.table, dplyr, tidyr, tidyverse, stringr, extrafontdplyr, psych, sf, maps, viridis, RColorBrewer, colorRamps, ggpubr
   - *install.packages(c("ggplot2", "datasets", "mlbench", "data.table", "dplyr", "tidyr", "tidyverse", "stringr", "extrafontdplyr", "psych", "sf", "maps", "viridis", "RColorBrewer", "colorRamps", "ggpubr", "scales", "ggthemes", "gridExtra"))*
- Download the course material
   - [Datasets](../master/Data/Workshop_data.zip)
   - [R code](../master/R_code/Rcode_ggplot_workshop.zip)
