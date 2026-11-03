# Practical R for Data Science

A collection of R Markdown assignments and practicals covering data import, summary statistics, visualization with ggplot2, t-tests, and the apply family of functions.

## Contents

| File | Topic |
|------|-------|
| `Practical_R_for_datascience_class_1.Rmd` | Introductory R practical |
| `R_Assignment_Importing_Data_into_R.Rmd` | Importing data into R |
| `Summary_Statistics_Functions_in_R.Rmd` | Creating summary statistics functions |
| `Use_ggplot2_geometric_functions.Rmd` | ggplot2 geometric functions |
| `Understanding_T-Tests_in_R.Rmd` | T-tests in R |
| `application_of_apply_sapply_vapply_lappay.Rmd` | apply, sapply, vapply and lapply |

## Folders

- **`data/`** – datasets used in the assignments
- **`Knit_Html/`** – all knitted HTML pages. Open these in a browser to view the rendered output without running any code.
- **`rsconnect/documents/`** – RStudio Connect publishing files

## Before Running the .Rmd Files

The file paths inside the R Markdown files point to locations on the author's computer. **Please update them to match where you saved the data on your machine.**

For example, change:

```r
data <- read.csv("C:/Users/author/Documents/project/data/file.csv")
```

to your own path, or use a relative path from the project folder:

```r
data <- read.csv("data/file.csv")
```

## Requirements

- R and RStudio
- Packages: `ggplot2`,`haven`,`RMariaDB`, `DBI`,`jsonlite`

## Author

**gannza**
