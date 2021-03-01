# Prosper Loan Data Exploration

## Dataset
The dataset contains approximatly 106,000 loans information with the related people occubation, empolyment, location,... information.
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000),
with the related features documentation [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

The exploation showed that: 
* 83% of are paid on regular basis
* 50% of the loans' amounts are less than 7000
* 84% of loans' APR values falls between the values [0.1, 0.35]
* 95% of loans' lender yeilds falls between the values [0.065, 0.32]
* Generally, the state does not affect on the count and the amount of the taken. Usually the percent of each states number of loans equals the state population percent of entire USA population with +-2%
* As it is known, people who have low payment jobs needs more loans, therefore, proffessionals and sales are of the people who take more loans. In contrast, people who had high payment jobs take less loans as judges and dentists
* Approximately 7% of the total number of loans are taken for Home Imporvement. The same goes for Bussines category
* Larger LoanOriginalAmount got lower BorrowerAPR values
* The average of loan amounts taken by employed and self-employed people is 8,700, while the average of loan amounts taken by retired, not-employed and part-time people is 4,490 dollars
* HomeOwners people take larger loans than who do not. the median value for HomeOwners is approx 10000, while the median value for the people who do not is 7000
* HomeOwners people take larger loans than who do not. The mean loan amounts for HomeOwners is approx 10000, while its approx 7000 dollars for people who do not homes
* CurrentlyInGroup people take much less loans than who are not. 9% of the people who take loans are belonging t oa group while all other people do not. The mean value for the loan amounts taken by CurrentlyInGroup is approx 6,600, while the mean value for the people who are not is 8,700.
* The results showed that OriginalLoanAmount falls in between 5000 and 6000 dollars for many scenraios. However:
  * For Current LoanStatus and Employed EmploymentStatus have higher average LoanOriginalAmount. They on average take more than 10,000 dollars
  * Generally Completed LoanOriginalAmout loans have lower values than other types especially for Retired, Part-time and Not employed people with the range of 3700 to 5000 dollars
  * Part-time people have the lowest LoanOriginalAmount for ChargedOff LoanStatus with approximatly 3900 dollars average value
  * The count of of the people in each EmploymentStatus and each LoanStatus for any employment status other than Employed is vrey few, for example the number of Part-Time people is 8 for the Past Due LoanStatus is 8, therefore we can see in the figure the high diversion in this category

## Key Insights for Presentation

For the presentation I focused on Studying **LoanOriginalAmount** and **LoanCounts** and the effect of the demographic features on them. I have started by showing the behaour of each feature alone (to show its affect on LoanCounts). The used charts where the histograms for the numrical variables and barcharts for the categorical variables to show the distribution of these variables.

Then, I have focused on LoanPriginalAmount and its relation with each of EmploymentStatus, LoanStatus, Having a home, belonging to a group,... I have used viloinboxes to show the high concentration loans's amounts. 

To show the relation between the features that had the most clear relation (from the studied features) on LoanOriginalAmount
pointplot is used as it help much in studying the resulted values for multivariate scenarios.

In all plots I have used the most readable and comofortable colors to the eyes, with theright font size and background grid.
