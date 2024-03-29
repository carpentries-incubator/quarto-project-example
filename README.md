# Project Example for the Workshop: Introduction to Reproducible Publications with Quarto Workshop

*Attention!* This is NOT the lesson repository. This is the GitHub repository for the project example used in the [Introduction to Reproducible Publications with Quarto](https://github.com/carpentries-incubator/reproducible-publications-quarto). Learners will be required to download the project example in order to follow along. 

**The project example folder is a simplified version of the original project available at: [https://osf.io/6mvq7](https://osf.io/6mvq7).**

Our example uses an adapted version of the data paper: 

Nitsch, F. J., Sellitto, M., & Kalenscher, T. (2021). Trier social stress test and food-choice: Behavioral, self-report & hormonal data. *Data in Brief*, 37, 107245. [https://doi.org/10.1016/j.dib.2021.107245](https://doi.org/10.1016/j.dib.2021.107245).

The data paper and its underlying data publicly available at [https://osf.io/6mvq7](https://osf.io/6mvq7) were adapted and used for educational purposes with the authors' permission.

------------------------------
## README

This directory contains the data and analysis scripts required to computationally reproduce some of the results and plots reported
in [https://doi.org/10.1016/j.dib.2021.107245](https://doi.org/10.1016/j.dib.2021.107245).

All provided code was written in R (R version 4.0.0 (2020-04-24) -- "Arbor Day") and should work with more recent versions. 
It requires the following packages to run the analysis code:
- tidyverse - 1.3.2
- stringi - 1.7.8
- bayesFactor - 0.9.12-4.5
- patchwork - 1.1.3
- usethis - 2.2.2 

The structure of the directory is:

root:

- `Reproducible-Publications-with-RStudio-Example.Rproj` # RStudio Project File
- `code` #Contains all runnable R script files
- `data` 
    - `processed`  # Contains processed data
    - `raw`      # Contains raw data
        - `foodchoice_data`  # Contains raw data from food choice task
- `output` # Contain all generated output
- `report`
    - `DataPaper-ReproducibilityWorkshop_files`   # Rendered files  
    - `fig`   # paper figures
- `LICENSE.md`
- `CITATION.md`
- `README.md`
- `_quarto.yml`

To repeat the analyses, 
1. Open the RStudio Project file.
2. Open and run analysis scripts (in order)

Graphic output is saved to output/plots
Data output is saved to output/data
Analysis results are saved in the environment / printed to the console
Paper output is saved to paper/output
paper/bin contains external files/code necessary for the proper formatting of the R Markdown paper output. 

**Note:** The `renv` branch has the same content as the `main` branch with the addition of having [renv](https://rstudio.github.io/renv/articles/renv.html) enabled for better reproducibility.

Please see citation.md for instructions on how to cite this workshop.

Please see License.md for instructions on how to re-use this material. 

Enjoy!

PS: For questions, please email ucsbcarpentry (@) ucsb.edu.

Contributors:

* Renata Curty (rcurty)
* Torin White (torwhite)
* Ian Lessing (ilessing)
* Greg Janee (gjanee)
* Julien Brun (brunj7)
* kristi Liu (kristi-sara)
