
# Understood Take Home <br>
Data Dictionary (Mroz) : https://rdrr.io/rforge/Ecdat/man/Mroz.html <br>
Pre-determined alpha = 0.05

```
1st Hypothesis
**ASSUMPTION** : 12 years of educational attainment signifies HS degree

The two populations refer to the sub-group with and without a High School degree (at least).

1.   Null hypothesis: The proportions of wives working for the two populations are equal.

2.   Alternative hypothesis: The proportions of wives working for the two populations are different. 
     (More specifically, the proportions of wives working is greater for those without HS degree)

Notations

1.  HS_yes_w = with High school degree, and 
2.   HS_no_w = without High school degree

Hypothesis
1.   Null         :  HS_yes_w = HS_no_w 
2.   Alternative  :  HS_no_w - HS_yes_w >0

```
![HighSchool](/images/H13.png)

We can observe that the proportion of wives working for the two populations seem different.
We need conduct t-test to determine if the difference is statistically significant.
###### T-Test Results

1.   t-statistic is positive
2.   p-value = 0.0006 (i.e. p-value < 0.05).

Hence, we are able to successfully reject the null 
hypothesis 




