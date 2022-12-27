# Healthcare Data Analysis
**DC Health Corp Data Analysis: Smoking Vs. Healthcare Charges**

# Executive Summary

**The health awareness campaign can begin focusing on obese smokers to start.**

- Smoking Status shows a very high correlation with charges, the other variables by themselves show moderate to low correlations.
- However, for Smokers, BMI shows a very correlation with charges showing the presence of double risk factors for overweight and obese smokers.
- People who walk over 5K steps per day show reduced charges, and those with over 8K daily steps show significantly reduced charges.
- Age shows three linear regions increasing with age, with obese smokers in the highest region, and a combination of non-obese smokers and nonsmokers of all BMI types in the middle region.
- For Smokers, we can create a high predictive model with an R^2 of 0.87 focusing primarily on Age and Obese/Non-obese variables, while for the nonsmokers, additional variables will be required to make an accurate prediction.

*Introduction*

- How can DC Health Corp improve their clients’ high leverage lifestyle variables to decrease overall medical expenses by $5k-$10k on average for high risk clients within 1 year?  

*Dataset Description*

- Data analyses these variables for 1,338 subjects. Variables include: Age, BMI, Charges, Children, Sex, Smoker (Y/N), Steps (steps per day). 

*Correlations*

- Smoker (0.79) shows the highest correlation with charges with steps (-0.31),  age (0.30), and BMI (0.20) showing only moderate correlations.

*Smoker*

- The median of smokers' charges ($34k) is significantly higher than the median of nonsmokers' charges ($7k).

*Steps*

- Clients who walk over 5K steps per day show reduced charges, while those with over 8K daily steps show significantly reduced charges.

*BMI/BMI Smoker*

- While BMI overall shows low correlations with charges, when separated by smoking status, we see that for smokers, BMI shows a very high correlation while for nonsmokers it is practically zero.

*Age*

- While age itself shows a weak correlation with charges, that is due to the presence of three separate linear regions; of which the top one is exclusively smokers, the bottom is non-smokers, and the middle one is a mix.

*Age/Smoker/BMI*

- For smokers, we are able to separate out the two linear regions -- the upper one is comprised almost entirely of obese BMI while the lower region is non-obese BMI. 

*Age/Nonsmoker/BMI*

- For non-smokers, with our current set of variables we have no means to distinguish the constituents of the two lines -- both contain all types of BMIs. 

*Regression: Smoker*

- For smokers, we can construct a regression model based on our previous findings by replacing BMI by a categorical variable, obese/non-obese, yielding a high R^2 of 0.87. 
 
*Regression: Nonsmoker*

- For nonsmokers, our regression model results in a low R^2 of 0.41.


*Next Steps*

The health awareness campaign can begin with the following priorities:
1) Smokers who are obese and older
2) The remaining obese smokers
3) Older non-obese smokers 
4) The remaining non-obese smokers
5) All should be encouraged to walk at least 8,000 steps daily

