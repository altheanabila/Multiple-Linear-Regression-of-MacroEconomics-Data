# Multiple-Linear-Regression-of-MacroEconomics-Data
I try to find out the correlation between Economic growth of Germany towards some independent variables such as Foreign Direct Investment, Export and Import data from 1971-2018. Using numpy, pandas, seaborn and matplotlib, the correlation could be presented and visualized comprehensively through tables and graphs.

1. Download the data from the website and arrange into 1 file

[website](https://www.macrotrends.net/countries/DEU/germany/foreign-direct-investment)

[dataMacroecon.xlsx](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Multiple1.xlsx)


2. Extracting into data panda frames

![testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon1.png)

3.Drop the date

![testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon2.png)

4. Define X and Y variables through this line of code

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon3.png)


5. Run this code to get the result of OLS. We can see that only variable Import that is statistically significant. The R squared presents weak correlation by only 32,1%.
`lm_multi = sn.OLS(y_multi, X_multi_cons).fit()`
`lm_multi.summary()`

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon4.png)


6. Visualize the graph in 3D graph

![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon5.png)
![Testimage1](https://github.com/altheanabila/Multiple-Linear-Regression-of-MacroEconomics-Data/blob/main/Macroecon6.png)

