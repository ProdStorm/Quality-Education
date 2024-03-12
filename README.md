# Analysis of the Implementation progress made by Ghana, South Africa, Kenya, and Zimbabwe toward achieving the SDG-4 targets.

## Contents
1. [Introduction](#introduction)
2. [Research Questions](#research-questions)
3. [Data Collection and Description](#data-collection-and-description)	
4. [Data Cleaning and Transformation](#data-cleaning-and-transformation)
5. [Exploratory Data Analysis with Power BI](#exploratory-data-analysis-with-power-bi)
6. [Findings](#findings)
7. [Conclusions](#conclusions)







### Introduction
Sustainable Development Goals (SDGs), established by the United Nations in 2015, is a collection of seventeen interlinked objectives designed to serve as a ‘shared blueprint for peace and prosperity for the planet, now and into the future.’ – Wikipedia.
SDG-4, also known as Quality Education, ensures inclusive and equitable quality education and promotes lifelong learning opportunities for all. This goal has 10 targets encompassing diverse aspects of education.
This analysis focuses on the primary education of some Sub-Saharan African countries - Ghana, South Africa, and Kenya - and aims to analyze the progress made toward achieving the under-listed targets.
- Target 4.1 - By 2030, ensure ALL boys and girls complete free, equitable, and quality primary education.
- Target 4.5 - By 2030, eliminate gender disparities in education and ensure equal access to all levels of education.
- Target 4.c - By 2030, substantially increase the supply of qualified teachers.

### Research Questions
- What is the percentage of the population of the relevant age group enrolled in primary education?
- Over the analyzed years, has there been a positive or negative trend in enrollments?
- What is the percentage increase in female enrollments?
- What is the trend of government expenditure on education?
- What is the ratio of males to females? Is the gender gap being reduced?
- Is the primary education sector understaffed? What is the pupil-teacher ratio? This will determine if every child gets proper attention from the teachers.
- What percentage of teachers have received the minimum training required for teaching?

### Data Collection and Description
The data analyzed to produce this report is accessible to the public at the World Bank Open Data and collected for a period of 11 years (2013 to 2022). The metadata indicators used for this analysis are: 
- Primary education gross enrollment
- Enrollments by Gender
- Pupil-Teacher ratio
- Trained Teachers
- Government expenditure on education. 

### Data Cleaning and Transformation
The steps taken when cleaning and transforming this data for analysis are listed below in the right order.
1.	Data downloaded had some columns in the wrong data type with missing values for some years.
2.	For each indicator, the data was filtered with Excel to display the countries of interest - Ghana, South Africa, Kenya, and Zimbabwe and then converted to the right data type.
3.	The forecasting function (FORECAST.EPS) was used to fill in the missing values using the interpolation technique. In cases where this function was unsuitable, the missing values were replaced with the mean values from other years.
4.	A new table was created for each country with the indicators as columns and years as rows and exploratory data analysis was done.

### Exploratory Data Analysis with Power BI
- Gender Disparity
  
 ![Gender Disparity](https://github.com/ProdStorm/Quality-Education/assets/82668824/ce4c4a24-a0bd-4ab3-b201-5d7deb66cd3d)


- Government Expenditure on Education

 ![Govt Expenditure](https://github.com/ProdStorm/Quality-Education/assets/82668824/891b1a87-0a51-4940-9222-08fd15efa36d)


- Pupil-Teacher ratio
  
 ![PT ratio](https://github.com/ProdStorm/Quality-Education/assets/82668824/a3354c24-5b55-4224-a560-021db8417032)



### Findings
1. Ghana
  - The number of females enrolled increased by 19.02% from 2012 to 2022.
  - Enrollments maintained a positive trend with 99.0% of the population of the relevant age group enrolled in 2022.
  - The ratio of males to females enrolled decreased from 1.04 in 2012 to 1.02 in 2022.
  - The pupil-teacher ratio decreased from 33 to 24 which is quite assuring that each child gets proper attention from the teacher.

2. South Africa 
  - The number of females enrolled increased by 12.23% from 2012 to 2022.
  - Enrollments maintained a positive trend with 96.5% of the population of the relevant age group enrolled in 2022.
  - The ratio of males to females enrolled decreased from 1.06 in 2012 to 1.05 in 2022.
  - The pupil-teacher ratio decreased from 33 to 24, also assuring that each child gets better attention from the teacher.

3. Kenya
  - The number of females enrolled decreased by 4.43% from 2012 to 2022.
  - Enrollments peaked in 2016 at 98.0% of the population of the relevant age group enrolled followed by an immediate decline that lasted up till 2020.
  - After the decline, the ratio of males to females enrolled increased drastically to 1.04 against 1.01 in 2012.

4. Zimbabwe
  - The number of females enrolled increased by 8.55% from 2012 to 2022.
  - The ratio of males to females enrolled increased from 1.02 in 2012 to 1.04 in 2022
  - Enrollments maintained a positive trend with 96.3% of the population of the relevant age group enrolled.
  - The pupil-teacher ratio increased from 36 to 41.

### Conclusions
1.	For other countries except Kenya, there is a significant increase in the number of females enrolled in primary education. With a cumulative increase between 8 to 20%, in no time, the number of enrollments for both genders will be almost equal with minimal difference. The gender gap is gradually being reduced.
2.	There is a decline in government expenditure in all countries except South Africa.
3.	With no standard to compare the pupil-teacher ratio with, this analysis can not say with certainty that primary education is understaffed but as expected, there is a negative correlation between the number of teachers and the pupil-teacher ratio. 
4.	Since the percentage of trained teachers in Zimbabwe is at 99.1%, it could be deduced that resources are being invested in training the already employed teachers instead of recruiting more.

#### Note
The incongruencies between the % of the population of the relevant age group enrolled and the population enrolled when compared against the previous years can be attributed to factors like mortality, migration, etc.
 
