# House-and-Urban-development
*The data sets are based on the American Housing Survey, AHS, national files from 1985 onwards. Housing-level variables include information on the number of rooms in the housing unit, the year the unit was built, whether it was occupied or vacant, whether the unit was rented or owned, whether it was a single unit or multi unit structure, the number of units in the building, the current market value of the unit and measure of relative housing costs. The dataset also includes variables describing the number of people living in the household, household income and the type of residential area. Example, urban or suburban. These are made available to the public by the US department of housing and urban development. These data are made available every two years. The latest data being available for year 2013. For our project we'll be using data from year 2005 onwards. That is we will use the data from 2005, 2007, 2009, 2011 and 2013.*

<br> 

## Variables 

![List-of-variables-to-be-used-in-Capstone_Page_1](https://user-images.githubusercontent.com/58776067/209517678-3f3d4f90-b0af-4561-8bd0-c07a95b4be87.png)
![List-of-variables-to-be-used-in-Capstone_Page_2](https://user-images.githubusercontent.com/58776067/209517698-ca4cf4ce-8b6c-4124-8629-bd2ee31e0f47.png)


<br>

## Questions
### 1.  Whether there are some differences in the market values of occupied versus not occupied housing units and whether these differences have a pattern over the period 2005 through 2013
- Descriptive statistics across the whole year
- Compare the means of two different population (occupied vs. un-occupied)
- conclusion


### 2. Is there a way to see if there was an effect of the 2008 subprime mortgage crisis, particularly, an effect on housing rent? 
- Merge the FMR across 2005 to 2013
- Descriptive statistics 
- Two-paired hypothese test
- conclusion

### 3. What factors predict or contribute to the housing or the current market value of single family units? (only single familiy units)
- The set of variables you used in the regression model and a brief justification for their use.
  - Set independent and dependent variables 
  - check relation of y and x -> if needs transformation: log-log? semi-log? etc. 
- The estimated regression model output from Excel
  - Check correlation among x variables -> Interactive factors? 
- Interpret the impact of various variables included in your model on the market value of housing units.
  - Managerial meanings 
  - Which factors play an important role? 
  
### 4. Predict future market value for the same properties.
- Use the built regression model 
  - Y variable of 2013 and x variables of 2011 by merging the data 
  - Data cleaning 
   - Use only the common housing unit
   - Housing values are above 1000 usd 
   - Only one familiy housing unit
- Evaluate the regression model 
  - Using existing model to get predicted housing value of 2013 
  - R square measure
  - Handout analysis 
   - Select 1000 housing units at random
   - Use the regression model to predict the selected x variables to get y variable
   - Compare the predicted y variables to the actual y variables of 2013
   - Calculate the "Mean absolute deviation" value to evaluate the model 

<br>

## Description
1. Understand descriptive statistics 
2. Know how to carry out test hypothesises of two different datasets
3. Create the linear regression model and interpret the data
4. Transform the regression model and interpret the data
5. Predict the y variable 
6. Evaluate the regression model
