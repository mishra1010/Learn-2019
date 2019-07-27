**Range,IQR and Outliers**

In this section we will discuss more on the measures of spread or dispersion of data.
-Range : max-min- It is the difference between the maximum vaue and minimum value in the list.

-Percentiles : when our list is in order, we can find percentiles. The most common ones are
.25th percentile(Q1)
.50th percentile(Q2 or median)
.75th percentile(Q3)

-IQR : stands for Inter Quartile Range and it is found by subtracting Q3-Q1

...The values of the minimum Q1,Q2,Q3 and the maximum make up what is called our 5 number summary.If we are given the 5 number summary, we 
can quickly find the range and IQR.
Example
![Example](/images/rangiq.png?raw=true "Example")

**Rstudio**
list = c(1,2,....)
command to see the 5 mumber summary-
fivenum(list)
output: 8.0,10.5,14.0,19.0,26.0
This gives us- 8 as mean, 10.5 as Q1, 14.0 as Q2(median), 19.0 as Q3 and 26.0 as the max

..The IQR is used to determine data classified as outliers.An outlier is an observation that is  "distant" from the rest of the data.
*Outliers can occur by chance or be measurement errors, so it is important to identify them.
*Any point that falls outside the interval calculated by Q1-1.5(IQR) and Q3+1.5(IQR) is considered outlier

Example
![Example](/images/rangiq1.png?raw=true "Example")

*There are other percentiles as well.The kth percentile means k% of the ordered data values are at or below that data value.
*Ex- if median is 100,then 50 % of the ordered data values fall at or below 100.Also (100-k)% represents the amount of ordered data that falls above the percentile data value.
*if we want to find the measurement that has a desired percentile rank, the 100pth percentile, is the measurement with rank(or position in the list) of nP+0.5, where n represents the number of data value in the sample.

Example-
![Example](/images/rangiq2.png?raw=true "Example")

Suppose we know the position(the order) of a value and we want to know what percentile it is ranked at.
![Example](/images/rangiq3.png?raw=true "Example")

Example
![Example](/images/rangiq4.png?raw=true "Example")


