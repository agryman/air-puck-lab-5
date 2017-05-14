# air-puck-lab-5

This repository ilustrates how to use R markdown to create a lab report.

The lab report was initially written by Sarah Costrell using LaTeX.
The LaTeX source for the report is stored in the ./latex directory.

The experimental data collected was initially stored in a Google Sheet at:
https://docs.google.com/spreadsheets/d/1bH66v2Zdjkj-Hx534CL9PSH7xxMWCSLk5lqBOr2claI/edit#gid=706587998
The data is stored in the ./data directory.

The goal of this project is to convert the lab report to R markdown
and generate all tables, graphs, and calculations using R commands embedded in the R markdown document.
To accomplish this, the Google Sheet is broken up into several CSV files which are then read by the R commands
when the lab report is generated from the R markdown.
Each CSV file has the structure of a simple table which can be read into an R dataframe.
Since all the tables, graphs, and calculations are driven from the data contained in the CSV files, any change to the
data gets consistently propagated through the lab report.
The R markdown for the lab report is stored in the ./R directory.

-- Arthur Ryman

