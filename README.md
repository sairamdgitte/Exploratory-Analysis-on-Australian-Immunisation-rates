# Exploratory-Analysis-on-Australian-Immunisation-rates
An extensive analysis on the Australian and Indigenous children’s immunization rate; determining if they seem statistically reasonable. Variation in immunization rates over Time, Age, and Location (state-wise) to make draw meaningful conclusions from the data.

# Requirements
1. Installing R: https://cran.r-project.org/bin/windows/base/
2. Installing RStudio Desktop: https://rstudio.com/products/rstudio/ 
3. All the R-packages mentioned within each markdowns in the .Rmd file

# Following are all the questions this project answers

# A1. Investigating the Distribution of Indigenous Australians
1. Using R to read, wrangle and analyse the data in Data1. Make sure you describe any complications you encounter and the steps you take when answering the following questions.
a. What regions have the maximum and minimum total Indigenous populations in 2016 and
2031?
b. What region/s have the maximum and minimum growth or decay rates of their total Indigenous population between 2016 and 2031?
Calculating these rates as the percentage difference between the 2016 and 2031,
 e.g., if 2031 population = 5500 & 2016 population = 5000,
then rate = (5500 – 5000) / 5000 = 500/5000 = 0.1, so 10% growth
c. Ploting and describing the growth or decay of the total Indigenous populations for the capitals of
the 8 state/territories across all time periods.
For these calculations, you will need to work out the growth/decay rates for each time period,
where the total population of the capital in time period N is compared to that in time period
N+1.
e.g., if 2017 population = 5050 and 2016 population = 5000,
then rate = (5050 - 5000) / 5000 = 50/5000 = 0.01, so 1% growth for 2016-2017

# A2. Investigating the Ages of Indigenous Australians 
1. Using Data1, which region has the highest percentage of children in its total 2016 population?
For this, calculate this as a percentage of the total population for a region. The ABS
commonly considers children to be under 15 years of age.
2. Data2 includes estimated populations measured for the years 2006-2016 and projected
estimates predicted for the years 2016-2031. Data1 just uses projected estimates. Using
Data2 only, calculate and discuss which state or territory has the highest percentage of
children in its total 2006, 2016 and 2031 populations.
3. Use R to build a Motion Chart comparing the total Indigenous Australian population of each
region to the percentage of Indigenous Australian children in each state/territory. Use the
region populations calculated from Data1 and the child percentage values calculated
from Data2. The motion chart should show the population on the x-axis, the percentage on
the y-axis, the bubble size should depend on the population.
Hint: an example of how to construct an R motion chart can be found on Moodle. You will
have to install the ‘googleVis’ package and may have to allow Flash to work on your browser
(see https://community.rstudio.com/t/gvismotionchart-from-googlevis-is-not-working-anysuggestion/6109/9 for advice on allowing Flash for Chrome). If you cannot get the example
script to work, contact your tutor.
4. Using the Motion Chart, answer the following questions, supporting your answers with
relevant R code and/or Motion Charts
a. Which region’s population overtakes that of another region in the same state/territory?
In which year/s does this happen?
b. Is there generally a relationship between the Indigenous Australian population size and
percentage of children in the population? If so, what kind of relationship? Explain
your answer.
c. Colour is commonly used in data visualisation to help understand data. Which aspect of
this data would you use colour for in your plot and why?
d. Are there any other interesting things you notice in the data or any changes you would


# B: Exploratory Analysis on Australian Immunisation rates
B1. Values and Variables
1. How many PHN areas doesthe data cover?
2. What are the possible values for 'PHN code'?
3. For each row, calculate the percentage of Australian children that are fully immunised (this is
the immunisation rate). What are the average, maximum and minimum immunisation rates?
Calculate the same for the group that are Indigenous Australian children. Do all of those
values seem statistically reasonable to you?

# B2. Variation in rates over Time, Age and Location
Generate boxplots (or other plots) of the immunisation rates versus year and age to
answer the following questions:
1. Have the immunisation rates improved over time? Are the median immunisation rates
increasing, decreasing or staying the same?
2. How do the immunisation rates vary with the age of the child?
Generate boxplots (or other plots) of the immunisation rates versus locations and answer the
following questions:
3. What is the median rate per state/territory?
4. Which states or territories seem most consistent in their immunisation rates?
recommend for the Motion Chart? 
