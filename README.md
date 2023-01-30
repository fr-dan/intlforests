# Functions for producing Forestry Statistics Ch. 9 International Forestry

:warning: **This is a prototype R package under constant development.**

:evergreen_tree: This packages provides functions to produce Forest Research's Forestry Statistics Chapter 9 publication as a [Reproducible Analytical Pipeline](https://dataingovernment.blog.gov.uk/2017/03/27/reproducible-analytical-pipeline/) (RAP).


# Background

[Forest Research](https://www.forestresearch.gov.uk/) produces Forestry Statistics as an annual compendium covering a number of topics in forestry and wood processing at the UK and GB level. Additionally, Chapter 9 reports on international forestry, presenting global figures by region alongside data for the UK and the EU.

The data are produced by the [United Nations Food and Agriculture Organisation](https://www.fao.org/home/en/) and released through their [Global Forest Resources Assessment](https://www.fao.org/forest-resources-assessment/en/) quinquennially and annually through [Forestry Production & Trade](https://www.fao.org/forestry/statistics/en/).

While the FAO data platforms have become increasingly sophisticated, allowing for the compilations and transformations required to produce the tables for Ch. 9 through their APIs. They require manual steps which do not align with the Civil Service's RAP strategy. This repository contains the bulk data downloads for the Forest Resources Assessment and Production & Trade, code for producing the tables and graphs in Chapter and a parameterised markdown report.


## To do list

### Dan

- Pivot and merge `data-raw/fao/` csvs to create a central tidy dataframe for the historic and current Forestry Production and Trade figures

- Write Rmarkdown file, with placeholders for tables, graphs and conditional language




