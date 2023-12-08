# Machine_Learning_R
Comparing different machine learning models in R 



# Abstract

This report focuses on loading and visualizing data, and testing different types of Machine learning models in R. Their performances were analyzed and discussed. The specific subject in question was data that did not follow a normal distribution in general. And the goal was to determine which model performed best under the circumstances to categorize different biomes based on enviornmenal factors.
The models used were: A Random Forest Classifier, Support Vector Machine(SVM), Decision Tree Classifier and Naive Bayes Classifier.


# Backgroundd
The Data being used comes from the U.S. Environmental Protection Agency (EPA Henceforth). There were two files, one for 2007 and one for 2012, each file contains information about the evaporation-to-inflow ratio of and water residence time for over a thousand lakes around the United States.[1] The below table briefly describes the column names of the data that were of interest to us. The data was originally collected as part of a study ''Lake Water Levels and Associated Hydrologic Characteristics in the Conterminous U.S.''[2] ''Lake Hydrologic study variables include water-level drawdown and two water stable isotope-derived parameters: evaporation-to-inflow (E:I) and water residence time. ''[2]
Given just the characteristics of an area, can a Machine Learning model classify the type of area.


*Name of Variable & Description*                          
ECO\_BIO         - Type of Enviornment     \\          
RT               - Retention time of water in each lake \\
EI               - Evaporation Inflow Rate  \\            
dD\_H2O          - Water Type used for comparison  \\     
d18\_H2O         - Water Type used for comparison   \\    

# references

https://catalog.data.gov/dataset/nars-hydrologic-data[1] \\
https://onlinelibrary.wiley.com/doi/10.1111/1752-1688.12817[2]
