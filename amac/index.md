<img src="https://raw.githubusercontent.com/lfc-math-cs/lfc-math-cs.github.io/master/amac/amac.png" class="img-fluid" alt="Responsive image">

## Data science

### What is it
* Data aquisition: cleaning,,transformation
* stats
* understanding of the situation What problems to solve? figuring out complex issues and how to solve them what particulars are because of what enviornment you are working in coding 
* One of the easier parts of data science. After learining python and establishing a genral understanding of how to go about learning code you can learn alot on the job. 
* Machine Learning:on the advanced end of the spectrum and large amount of work with machine learning in research or prediction based fields

### Why do it
* big money (70-100K per year with associates degree)
* quite fun(might me just me)
* High chance for fortune 500, contracting work, startups (Facebook, google, IBM)
* desireable in resume even for economic or finance majors its very impressive skill to know and shows versitility
	
### what can you do with it

You gather all the information needed to answer big questions 

Q: which users spend the most time on the shopify and why</br>
Method: take the top 90th percentile users in terms of time spend and aggregate there user behavior by activity and compare to the rest of the users</br></br>
Results: you see they spend a large amount fo time on photo uploading for there stre because they need to uploade multiple images per item for multiple perspect ives</br></br>
Action: improve the Photo upload process by allowing batch uploads. Develop predictive models for diffrent research</br></br>
Create backend and support existing architecture of things like MySQL databases and websight user analytics

</br></br></br>

Data Engineers </br>
Develops and constructs architecure like data bases and data tracking tools logisticts and operational research 

Data Analytics </br>
analysis data with descriptive statistics to build models and find isights or patterns in data that could be useful to companies

Research Scientists/ Data Science Core/ ML engineers</br>		
Heavy research fosuc with predictive modeling and large scale data prossesing to interprite results of generated models

## TOPICS

Sample problems done by data science / MCM stuff

### Programing

1. Pandas, basics of coding, csv/database views
2. Visualization of data, Matplotlib / Seabass: [Github Course](https://github.com/pmaji/practical-python-data-viz-guide)
3. Database collection,WebScrapping
4. Machine learning, diffrent types, uses and pros/cons
5. Machie learning, how it works


### Math/Statistics
1. Pearson Correlation Coefficient: <br>
Measures linear correlation between x and y (between -1 and +1; 0 = no correlation) The 2 var have to be measured on either an interval or ratio scale, but don’t need to be on the same scale; don’t have to be the same units; doesn’t differentiate between dep/independent variables;PCC is NOT the slope of the line of best fit 
2. PCA (Principal Component Analysis) <br>
Can be used to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables called principal components. Further info here: https://en.wikipedia.org/wiki/Principal_component_analysis 
3. Clustering Algorithms
4. Survival Analysis/ Time Series
5. Spearman’s rank-order/Kendall’s Tau Correlation 
6. Utility Functions <br>
Adjusts data values to make data distribution more uniform and confine values to a specified range.
7. ARMA (Autoregressive Moving Analysis) <br>
Given a time series of data Xt, the ARMA model is a tool for understanding and perhaps predicting future values in this series (wikipedia, need to find something better to quote) - appropriate when a system is a function of a series of unobserved shocks as well as its own behavior AR – regressing the variable on its own lagged values and MA- modelling the error term as a linear combination of error terms  
AR model: Xt = c + ΣaiXt-i + et where c is the constant, ai are parameters, and et is white noise 
MA model: Xt = m + et + Σbiet-i where m is E[X] (often assumed to be zero), bi are parameters  
and et & et-i are white noise error terms 
ARMA: Xt = c + et + sum term for AR + sum term for MA 
    Can be implemented in: R, Matlab, Stata, SAS... everything 
8. Gaussian (Normal) distribution <br>
Continuous function, approximates the exact binomial dist of events 
Normalized version has the 68, 95, 99.7 rule (1, 2, and respectively 3, stdevs from mean) 
9. t-tests <br>
Observed data is from random samples of skewed normal distributions 
10. Time series <br>
Time series order of difference equations (order=max lag included on the right side) 
11. Predicting nr of language speakers:  <br>
Malthusian Growth Model (population growth rate does not change over time) - can use to measure a population at one point in time or a part of the population which has a certain characteristic at one point in time or Logistic growth model  

12. Tikhonov Regularization (known in stats as ridge regression) - also known as a machine learning algorithm <br>
The standard approach is OLS linear regression, however if no x satisfies the equation (or more than one x does) [the solution is not unique] the problem is said to be ill posed. In such cases, OLS estimation leads to an over-fitter or under-fitted set of equations. Tikhonov regularization is used to give preference to a particular solution with desirable properties. Can be used for general multivariate normal distributions for x.  