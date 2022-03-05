# PyBer_Analysis
Module 5

## Overview of the Analysis

Purpose of this project was to look at ride share data across several city and city types and provide different views through tabes as well as different charts.  Initially two
sets of data were used which comprised of city data and individual ride data in that city for a specified period.  Using the common index of city we were able to combine and
further analyze the merged dataset.  A sample of that merged data can be seen here:
![](https://github.com/lavec0324/PyBer_Analysis/blob/main/analysis/merged_data.PNGG)

Only three files are necessary for this analysis:

   * [PyBer_Challenge.ipynb](https://github.com/lavec0324/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb) - Jupyter Notbook created for analysis
   * [city_data.csv](https://github.com/lavec0324/PyBer_Analysis/blob/main/Resources/city_data.csv) - City Data
   * [ride_data.csv](https://github.com/lavec0324/PyBer_Analysis/blob/main/Resources/ride_data.csv) - Ride Data

This analysis could be used to determine what types of areas see more rides, the average cost of those rides, and the impact the time of the year has on those results.

## Results

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

Total rode


## Summary

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

Requirements ***************

Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)

Analysis (14 points)
The written analysis has the following:

Overview of the analysis:

The purpose of the new analysis is well defined. (3 pt)
Results:

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
Summary:

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)



Examples *************

# School_District_Analysis - Module 4 Challenge

## Overview of Project

This project is intended to analyze school data and student data for the district.  This involves data cleansing activtiies, removing data 
that is deemed questionable, then providing results before and after removing the questionable records.  This data will provide insight into 
the district to make decisions on such things as spending based on school sizes as well as performance.

Only three files are necessary for this analysis:

   * [PyCitySchools_Challenge.ipynb](https://github.com/lavec0324/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) - Jupyter Notbook created for analysis
   * [schools_complete.csv](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/schools_complete.csv) - School data file
   * [students_complete.csv](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/students_complete.csv) - Student data file

All other files in the repo are working data only or images.

## Results
Results: Using bulleted lists and images of DataFrames as support, address the following questions.

###	How is the district summary affected?

District Summary Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/district_summary_before.PNG)

District Summary After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/district_summary_after.PNG)

####	How is the school summary affected?

School Summary Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/school_summary_before.PNG)

School Summary After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/school_summary_after.PNG)


####	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School's Performance Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/top_five_before.PNG)

Thomas High School's Performance After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/top_five_after.PNG)

####	How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade

* Math - 9th grade math was dropped, all other remained the same

Math Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/math_score_by_grade_before.PNG)

Math After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/math_scores_by_grade_after.PNG)

* Reading - 9th grade math was dropped, all other remained the same

Reading Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_before.PNG)

Reading After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_after.PNG)

Scores by school spending

* While there were residual differences when rounded up there were no changes in spending, size, or type.

Spending Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/spending_before.PNG)

Spending After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/spending_after.PNG)

Scores by school size

Size Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/size_before.PNG)

Size After

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/size_after.PNG)

Scores by school type

Type Before

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/type_before.PNG)

Type After 

![](https://github.com/lavec0324/School_District_Analysis/blob/main/Resources/type_after.PNG)

## Summary

Summary:  Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Overall there doesn't seem to be a large change in percentages, the four most prevalent changes are:
* District math scores dropped from 75 to 73.9
* Disctrict reading scores dropped from 86 to 84.7
* Thomas high school overall passing dropped from 90.95 to 90.63
* Ninth grade scores were dropped from Thomas high school

This might conclude that the grades that were dropped did not show a material difference overall which could indicate that there was no foul play in those grades.
