# Index to evaluate the democracy level of a country

Nowadays many countries are considered as democracies but the conditions which define a country to be democratic remain unclear. 

Each year the Economist publishes a ranking of countries according to their democracy level. Each countries has a score which is between 0 and 10 (0 = the country is not a democracy and 10=the country is a perfect democracy). This score is the mean of 5 criterium : 
- Functionning of govenrment
- Political partipation
- Political culture
- Civil liberties
- Electoral process and pluralism

The main objective of our project is to identify the variables that are the most relevant to qualify a democracy. 

In this way, we use 3 different datasets :

- "donnees" corresponds to data of 167 countries from the economist with the variables "Gscore" (which corresponds to the democracy level between 0 and 10) and the five variables quoted above.


- "Tableau_complet_Gscore" which contains once again the variable Gscore with 21 other variables. The goal is to analyze these 21 variables and check if they are relevant to explain the Gscore.  

- Third dataset.



In order to find the best variables to define a democracy with use several statistics tools such as :
- PCA
- Linear regression
- Logistic model
- classification and regression tree
- random forest
- comparison test of mean and variance
- clustering

