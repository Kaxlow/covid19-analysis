# Analysis of Covid-19 data

In this project, data on Covid-19 deaths and cases reported in the US and around the world is collected from the New York Times and John Hopkins University's Center for Systems Science and Engineering (CSSE). Data from 2020 to 2021 is prepared, explored, and then visualized in different ways to draw conclusions on the impact of Covid-19 across different places.

## Methodology

The data analysis is done in R where _tidyverse_ is primarily used to clean data and prepare it in a suitable format for exploration and visualization. Data is explored at different scopes such as for US counties, then states, and then for different countries. Deaths and cases are also measured in different ways such as the cumulative total, new deaths and cases per day, and then 7-day averages of new deaths and cases per day. These measures are also calculated on a per 100,000 population basis. Data is visualized using _ggplot_ to show trends and key information.

## covid19_analysis.rmd

This is an R Markdown file that contains the R code used to read data from the abovementioned sources, prepare the data in suitable formats, explore the data is the ways described in the methodology section, and then visualize the data through charts. The file includes accompanying explanations for each section.

## covid19_analysis.pdf

This is a knitted .pdf document created from the `covid19_analysis.rmd` file using RStudio. The file shows the results and charts generated from running the R code, along with accompanying explanations for each section.

## Other files

The `*.csv` files contain input data referenced by the R Markdown file.
