
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
We need to conduct t-test to determine if the difference is statistically significant.
##### T-Test Results

1.   t-statistic is positive (0.2014)
2.   p-value = 0.0006 (i.e. p-value < 0.05).

Hence, we are able to successfully reject the null 
hypothesis 


```
2nd Hypothesis

The two populations refer to the sub-group with and without work.

1.   Null hypothesis: The mean of the number of children under age 6 for the two populations are equal

2.   Alternative hypothesis: The mean of the number of children under age 6 for the sub population with 
                             work is greater than that of without work.


Notations:
1.   yes_work = number of children under age 6 belonging to employed women
2.   no_work = number of children under age 6 belonging to unemployed women


Hypothesis

1.   Null         :  mean(yes_work) = mean(no_work)
2.   Alternative  :   mean(yes_work) > mean(no_work)
```

![Child6](/images/H23.png)


##### RESULTS

1.   t-statistic is positive (5.996)
2.   p-value = (3.14*e-09)/2 (i.e. p-value < 0.05)


Hence, we are able to successfully reject the null hypothesis

```
3rd Hypothesis

The two populations refer to the sub-group of wifes with both parents with atleast 7 years of education, and those without.

1.   Null hypothesis: The proportions of wives working for the two populations are equal.

2.   Alternative hypothesis: The proportions of wives working for the two populations are different.
     (More specifically, the proportions of wives working is lower for those with both parents 
      with atleast 7 years of education)


Notations:

1.  yes_parents_edu = proportion of wife working, with both parents have atleast 7 years of education, and 
2.  no_parents_edu = proportion of wife working, with at least one parent has less than 7 years of education


Hypothesis

1.   Null         :  yes_parents_edu = no_parents_edu 
2.   Alternative  : no_parents_edu - yes_parents_edu > 0

```


![Child6](/images/H32.png)


##### RESULTS

1.   t-statistic is positive (2.473_
2.   p-value = (0.0136)/2 (i.e. p-value < 0.05)


Hence, we are able to successfully reject the null hypothesis
