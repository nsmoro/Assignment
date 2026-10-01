# CENT_Assignment
This document contains the solutions to the take-home assessment tasks for the Bioinformatics Research Scientist role at St. Jude Children’s Research Hospital.
The analysis is implemented in R and documented using R Markdown.

---

## Main Report

The primary deliverable is a rendered R Markdown report:

- **`tasks_Morosini.html`** – rendered analysis report (recommended starting point)
- `tasks_Morosini.Rmd` – R Markdown source containing all code and narrative

Please open the `tasks_Morosini.html` file in a web browser to view the full analysis.

---

## Repository Structure

- `data/` – input data objects
- `data_clean/` – processed and cleaned data used for analysis
- `part1/`, `part2/`, `part3/` – analysis components corresponding to different parts
  of the assignment

All code used in the analysis is contained directly in the R Markdown document.

## Notes on data files

A large serialized R workspace object (workspace.rda) generated during analysis
is not included in the repository to keep it lightweight. All figures and results
are fully reproducible from the provided R Markdown document.

---

## How to Reproduce the Analysis

### Requirements

- R (version 4.2 or higher recommended)
- RStudio (optional but recommended)

### To re-render the report

From R or RStudio, run:

```r
rmarkdown::render("tasks_Morosini.Rmd")
```
---

## Author

Prepared by: **Silva Morosini, Natalia**  
Date: **April 9, 2026**
