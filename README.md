# Project02_Data_Wrangling
*Ulrike Anklam*

*DATAFT- Berlin- August 2020*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
This project is supposed to show data cleaning, wrangling and manipulation skills acquired after week two of the bootcamp. The goal is it to perform as many manipulations as possible on the given table in order to transform it into a useable dataset for further analysis. 

## Dataset
The dataset for this project was downloaded from [kaggle.com](https://www.kaggle.com/teajay/global-shark-attacks/version/1). It is a messy dataset, which consists of data from shark attack incidences compiled by the [global shark attack file](http://www.sharkattackfile.net/index.htm).

## Database
It only consists of one table, stored as a csv file. 

## Workflow
- importing the file with pandas 
- gathering general information about the table, such as number of columns and rows and taking a first look the top (head, first 5 rows) of the table
- handling null values in the dataset, dropping columns and rows with too many null values 
- trying to change datatype of certain columns if current type is not suitable
- eliminating false data in certain columns
- checking for columns that contain the same information than another column(duplicate information) and deciding if they should be dropped or preserved
- changing whitespace in columnnames to underscore
- exporting as a csv file

## Organization
The repository consists of one notebook file, the original csv file and the csv file after the data wrangling process. To achieve the results that are documented in the notebook I used the lecture matrial from class, notes from these lectures, the online lesson material, as well as online documentation. 

## Links

[Kaggle.com](https://www.kaggle.com/teajay/global-shark-attacks/version/1)  
[Global Shark Attack File](http://www.sharkattackfile.net/index.htm)  
[GitHub](https://github.com/Ulli-H/Project02_Data_Cleaning.git)  
