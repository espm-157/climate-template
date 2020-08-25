

This repository is a template for every teams climate module repository. This is the first module of ESPM 157, intended to
explore global temperature data to understand how the earth's climate is warming. 

## assignment

All work for this assignment is in the `assignment` directory.  Code is contained in the `climate.Rmd` notebook, and final rendered output files (`climate.md` and associated files) are in the `assignment` directory as well. The general rubric you will be graded on is found in the `Rubric.md` file. 

## Special files

Additionally this repository, and all team repositories, includes most of the special files found here:

### Common files

- `README.md` this file, a general overview of the repository in markdown format.  
- `.gitignore` Optional file, ignore common file types we don't want to accidentally commit to GitHub. Most projects should use this. 
- `climate-template.Rproj` an R-Project file created by RStudio for it's own configuration of the repo files.  Some people prefer to `.gitignore` this file, it is optional for team repos to ignore or commit their own `<REPO-NAME>.Rproj` file. 

### Infrastructure for Testing

- `DESCRIPTION` a metadata file for the repository, based on the R package standard. It's main purpose here is as a place to list any additional R packages/libraries needed for any of the `.Rmd` files to run.
- `.github/workflows/main.yml` defines the Continuous Integration testing script for running the `.Rmd` files to confirm reproducibility.  



