# Importing CSV and Excel Files in R

This repository provides a simple example of how to import CSV and Excel (XLSX) files in R using commonly used packages.
The goal is to demonstrate a clear and beginner-friendly workflow for loading tabular data into R for further analysis.

# Requirements

Make sure the following packages are installed:

install.packages("readr")
install.packages("readxl")

# Importing CSV Files

CSV files can be imported using the readr package:

library(readr)

data_csv <- read_csv("data/example.csv")
head(data_csv)

# Importing Excel (XLSX) Files

Excel files can be imported using the readxl package:

library(readxl)

data_xlsx <- read_excel("data/example.xlsx")
head(data_xlsx)

Project Structure
project/
│
├── data/
│   ├── example.csv
│   └── example.xlsx
│
├── scripts/
│   └── import_data.R
│
└── README.md

# Purpose

This project is intended for beginners who want to learn how to quickly load CSV and Excel datasets into R for data analysis, visualization, or preprocessing tasks.

# License

This project is open source and available under the MIT License.
