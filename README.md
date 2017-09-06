# 

[![Build Status](https://travis-ci.com/espm-157/2017-instructor-carl.svg?token=HrMbVv2Gfn8BzLNkrr1q&branch=master)](https://travis-ci.com/espm-157/2017-instructor-carl)

This repository is a template for your team's repository.

## assignment

All work for this assignment should be in the `assignment` directory.  You will work in the `climate.Rmd` notebook, and commit your rendered output files (`climate.md` and associated files) in the `assignment` directory as well.

## Special files

All team repositories will also include most of the special files found here:

- `.drone.yml`: A configuration file for automatically running [continuous integration]() checks to verify reproducibility of all `.Rmd` notebooks in the repo.  If all `.Rmd` notebooks can render successfully, the "Build Status" badge above will be green (`build success`), otherwise it will be red (`build failure`).  

- `tests/render_rmds.R` an R script that is run to execute the above described tests, rendering all `.Rmd` notebooks. 

- `.gitignore` Optional file, ignore common file types we don't want to accidentally commit to GitHub. Most projects should use this. 
- `<REPO-NAME>.Rproj` Optional, an R-Project file created by RStudio for it's own configuration.  Some people prefer to `.gitignore` this file.
- `DESCRIPTION` a metadata file for the repository, based on the R package standard. It's main purpose here is as a place to list any additional R packages/libraries needed for any of the `.Rmd` files to run.
- `README.md` this file, a general overview of the repository in markdown format.  




