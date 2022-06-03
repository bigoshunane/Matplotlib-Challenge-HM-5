# Pymaceuticals Inc Data Analysis

## Background and Objective of the project

The aim of this project is to apply python libraries matplotlib and pandas to generate tables and figures required for technical report of the study of squamous cell carcinoma (SCC) a commonly occurring form of skin cancer which is conducted in pharmaceutical company based out of San Diego. The company identified 249 mice with SCC tumor growth which were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of the study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

Datasets taken from the pharmaceutical company with folder named Pymaceuticals and developed matplotlin computation on jupyer notebook with file name pymaceuticals_starter.jpynb are found in repository.

# Final report includes the following:

  -  Summary Statistics
  -  Bar and Pie Charts
  -  Quartiles, Outliers and Boxplots
  -  Line and Scatter Plots
  -  Correlation and Regression
  -  Observations and Insights
  
  
-  Summary Statistics  
 
 ![Table 3](https://user-images.githubusercontent.com/84547558/150945601-072a9c5d-2f5e-4965-b327-c0c3d0b65449.png)


  -  Bar chart

![Fig 1](https://user-images.githubusercontent.com/84547558/150945681-707c834f-8209-42ba-b715-a8a179349a92.png)


  -  Pie chart

![pie](https://user-images.githubusercontent.com/84547558/150945919-4f38a238-eb6b-435f-bb2d-87920408b79f.png)


  -  Boxplot

![Fig 4](https://user-images.githubusercontent.com/84547558/150946279-db77a13c-4ff1-49d3-a74a-f993b049cb94.png)


  -  Scatter plot

![Fig 7](https://user-images.githubusercontent.com/84547558/150946408-ee4b1d9c-80eb-429e-aeda-67027ff98ca8.png)


  -  Line plot

![Fig 6](https://user-images.githubusercontent.com/84547558/150946590-e3d8301e-25ec-44be-a783-28bb62cc38bf.png)


  -  Correlation and Regression plot

![Fig 8](https://user-images.githubusercontent.com/84547558/150946791-ad13b46d-1e30-4d1d-b586-5d54bcc00d47.png)


## Observations and Insights

-  Among tested drug regimens including placebo, Ramicane seems to be the most effective in reducing tumor growth, showing lower the median value.    
-  Mice treated with Capomulin demonstrated the highest survival rate compared to the mice treated with the other eight treatment regimens used in the study (Fig.1). Capomulin has the second lowest tumor volume median after Ramicane (Table 2). Survival rate of Ramicane regimen comes after Capomulin, however,
 its efficacy in the tumor volume reduction over the period of study is the highest out of all analyzed treatments.
-  Mice gender did not demonstrate any effect on efficacy of the studded treatments. Mice population used in the study had 51 % of male mice versus 49 % of 
 female mice (Fig. 3) and decrease or increase in the tumor volume was demonstrated in both genders equally and depended only on the type of a regimen being 
 used as a treatment.
-  The final tumor volume measurements of mice treated with Capomulin and Ramicane showed that two mice out of twenty-five treated with Capomulin developed an
 increase in the tumor growth volume (Table.4), while all twenty-five mice treated with Ramicane had reduction in the tumor volume.
-  The observation of correlation between body weight and average tumor volume among mice treated with Capomulin showed that tumor volume is directly related 
 to the weight of a tumor-bearing mouse.
-  From regression analysis we can observe how much the average tumor volume will change as weight of mice changes.
 The R-squared value is 0.70, which means the model fits the data by 70%, wich is sound to predict the data from the model.
-  Capomulin treated mice demonstrated strong improvement in the tumor volume  among others and out of all analyzed regimens Capomulin provided second best 
results after Ramicane regimen. More study needs to be done to have a farther analysis.

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
