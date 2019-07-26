# Learn-2019 - Courtesy Courseera
------------------------------------------------------------------- Statistics---------------------------------------------------
**Week1**
Day1

Types of Data-
1. Population data - includes all the data that we are studying
2. Sample Data - a subset of the data from the population data

Example1-

![Example1](/images/typesofdata.jpg?raw=true "Example1")

Example2-
![Example2](/images/type0fdata2.png?raw=true "Example2")


Variable
is a property of an individual that can assume more than one value. These can be classified as-
1. Categorical (qualitative) - represents the type of quality the data may have. ex- type of car, color
2. Quantitative(Numeric) - can be classified as discrete or continuous - these are measurements
Discrete variables are countable. ex- number of lives given in a play in video game
Continuous can take any value in an interval. ex- amount of time we wait in a line at a cinema hall

Examples
![Examples](/images/categoricalvsquantitative.png?raw=true "Examples")

**Measures of Center**
A very important question to be answered in data is about the location of its center. MOC includes-
1. mean - denoted by mu for population mean and xbar for sample mean (calculate mean by adding all values and dividing by how many)
2. median - is found by putting data in the list from small to largest and find the middle value and if there are 2 middle value, average those to find the median.
3. mode - value that ocurs most often in a list. Used as a description of center for categorical data.

*Example1*
![Examples](/images/meanmode.png?raw=true "Examples")

*Example2 - Using R-studio*
list=c(type in all the values)

*command for mean*
mean(list)
*command for median*
median(list)

Mode is not available as a function, so we need to first
sort(list)
Then pick out the one that occurs the most as the answer

*Example3*
![Examples](/images/meanmode2.png?raw=true "Examples")

*Example4*
![Examples](/images/meanmode3.png?raw=true "Examples")


**Day 3**

**Standard Deviation and Variance**
Important question to answer about data is about its spread or dispersion.
Population Standard Deviation - (Sigma)σ is the average distance data values fall from the mean.
Population Variance - σ^2 is the square of population standard deviation.

How to find Variance?
Variance is the average of the squared data values from mean.
![Examples](/images/Variance.png?raw=true "Examples")




