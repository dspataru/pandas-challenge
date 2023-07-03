# pandas-challenge
Module 4 Challenge - PyCitySchools


## Background

This repository contains an analysis of city school district data. The project uses two datasets:
(1) [schools_complete.csv](https://github.com/dspataru/pandas-challenge/blob/main/Resources/schools_complete.csv) : contains data pertaining to the schools including School ID, school_name, type, size, and budget.
(2) [students_complete.csv](https://github.com/dspataru/pandas-challenge/blob/main/Resources/students_complete.csv) : contains data about students at each school and their Student ID, student_name gender, grade, school_name, reading_score, and math_score.

The above two csv files can be found in the Resources folder of the current repository. Python's pandas library is used to import, merge, and sort the data into dataframes to analyze school and standardized test data to discover trends that might help to make strategic decisions regarding future school planning.

The IDE used for this challenge is Jupyter Notebook.

#### Key Words
Jupyter Notebook, Pandas, Python, DataFrames, DataSets.

## Observable Trends

## Table of Contents

## Import Dependencies and Setup

## Load, Read and Merge the Data

## District Summary

The district summary provides a high-level snapshot of the district's key metrics in a DataFrame that includes the following:
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading) 
* % overall passing (the percentage of students who passed math AND reading)

## School Summary

The school summary is a DataFrame that contains the following key metrics about each school:
* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

## Top Performing Schools (By % Overall Passing)

The top_schools DataFrame sorts the schools by % overall passing in descending order and takes the top five schools.

## Bottom Performing Schools (By % Overall Passing)

The bottom_schools DataFrame sorts the schools by % overall passing in ascending order and takes the first five schools (aka the lowest ranked schools).

## Math Scores by Grade

This DataFrame contains the average math scores for students from grades nine to 12 at each school.

## Reading Scores by Grade

This DataFrame contains the average reading scores for students from grades nine to 12 at each school.

## Scores by School Spending

The spending_summary DataFrame breaks down school performance based on the average spending ranges per student. The spending budget is split into four spending bins: <$585, $585-630, $630-645, and $645-680. The average spending amount per student is calculated for each bin. The spending_summary DataFrame includes the following metrics:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

## Scores by School Size

The size_summary DataFrame breaks down school performance based on the size of the school. The school size is split into three bins: small (<1000 students), medium (1000-2000), and large (2000-5000). The size_summary DataFrame includes the following metrics:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

## Scores by School Type

The type_summary DataFrame shows the school performance based on the school type: District or Charter. The type_summary DataFrame includes the following metrics:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


