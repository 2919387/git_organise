# git_organise

This repository contains the organised files for Homework Q3.

This repository contains 3 repositories:
- src: Contains the R scripts used by this project
- data: Contains the data used by the R scripts
- out: Contains the data tables and figures produced by the R scripts

The file "data-sources.txt" contains information about the source of the data found in "data".

To run this code, download this repository, open the R scripts from "src" in R, and set the working directory to the "git_organise" repository. Run "combine-data.R" first, which combines the data from "data" into a new csv file ("average-rainfall.csv", in "out"), followed by "make-plot.R", which creates the figure "result.png" (in "out") using this csv file.
