## Bike Sharing Demand Case Study
The purpose of this case study is to build a multiple linear regression model for the prediction of demand for shared bikes.

### Table of Contents
* [Problem Statement](#problem-statement)
* [The Approach](#the-approach)
* [Repository contents](#repository-contents)
* [Python libraries](#python-libraries)
* [Model Summary](#model-summary)
* [Key Takeways](#key-takeways)
  
## Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

**The company wants to know:**
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.
  
**Objective:**
Build a **Linear Regression model** for the demand of shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.

## The Approach
1) Reading and Understanding the Data
2) Data manipulation and cleaning
3) Visualising the Data
4) Data Preparation
5) Splitting the Data into Training and Testing Sets
6) Building model
7) Residual Analysis of the train data
8) Making Predictions Using the Final Model
9) Model Evaluation

## Repository contents
| File | Description |
|:-----|:------------|
| Python notebook | It contains the complete detailed code along with necessary output to solve the problem|
| PDF | Answered the asked subjective questions. |
| README.md | This file briefs about the project. |
| day.csv | The bike sharing case study data set. |
| data_dictionary.txt | Meaning of the variables in the dataset. |

## Python libraries
1. numpy
2. pandas
3. seaborn
4. matplotlib
5. sklearn
6. statsmodels

## Model Summary 
```
                           OLS Regression Results                            
==============================================================================
Dep. Variable:                    cnt   R-squared:                       0.822
Model:                            OLS   Adj. R-squared:                  0.819
Method:                 Least Squares   F-statistic:                     289.4
Date:                Sat, 09 Dec 2023   Prob (F-statistic):          2.26e-182
Time:                        20:38:05   Log-Likelihood:                 478.75
No. Observations:                 510   AIC:                            -939.5
Df Residuals:                     501   BIC:                            -901.4
Df Model:                           8                                         
Covariance Type:            nonrobust                                         
==================================================================================
                     coef    std err          t      P>|t|      [0.025      0.975]
----------------------------------------------------------------------------------
const              0.3248      0.019     17.224      0.000       0.288       0.362
yr                 0.2366      0.009     27.738      0.000       0.220       0.253
holiday           -0.0907      0.027     -3.362      0.001      -0.144      -0.038
temp               0.3445      0.024     14.181      0.000       0.297       0.392
windspeed         -0.1475      0.026     -5.742      0.000      -0.198      -0.097
sep                0.0689      0.016      4.289      0.000       0.037       0.100
light_snowrain    -0.2803      0.026    -10.970      0.000      -0.330      -0.230
misty             -0.0795      0.009     -8.761      0.000      -0.097      -0.062
spring            -0.1513      0.013    -12.080      0.000      -0.176      -0.127
==================================================================================
```
## Key Takeways

1. Temperature Impact: When it's hot, expect more bike demand. Action: Prepare for high demand in hot weather.
2. Yearly Trend: Demand increases YoY. Action: Stay focused on business sustainability.
3. September Spike: Demand rises around September. Action: Be ready to manage increased demands in September.
4. Holiday Downturn: Demand decreases during holidays. Action: Promote offers or events to boost usage during holidays.
5. Seasonal and Weather Impact: Decrease during spring and bad weather. Action: Prepare for higher demand later by servicing bikes and docks.

## Contact
Created by [Anupam Maiti](https://www.linkedin.com/in/anupam-maiti/) - feel free to contact me!
