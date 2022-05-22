# Exploring socioeconomical datasets to model the democratic level of countries

Nowadays many countries are considered as democracies but the conditions which define a country to be democratic remain unclear. 

Each year the Economist publishes a ranking of countries according to their democracy level. Each countries has a score which is between 0 and 10 (0 = the country is not a democracy and 10=the country is a perfect democracy). This score is the mean of 5 criterium : 
- Functionning of govenrment
- Political partipation
- Political culture
- Civil liberties
- Electoral process and pluralism

The main objective of our project was to identify the variables that are the most relevant to qualify a democracy. 

In this way, we used 3 different datasets:

- "donnees" (The Economist dataset) corresponds to data on 167 countries from the Economist with the variables "Gscore" (which corresponds to the democracy level between 0 and 10) and the five variables quoted above. (Link to the Economist intelligent Unit website: https://www.eiu.com/n/)


- "Tableau_complet_Gscore" (Wikipedia dataset) which contains once again the variable Gscore with 21 other variables extracted from Wikipedia. The goal is to analyze these 21 variables and check if they are relevant to explain the Gscore.  

- A third dataset (OWD dataset) that we built thanks to this website: https://ourworldindata.org/



In order to find the best variables to define a democracy we used several statistics tools such as:
- PCA
- Linear regression
- Logistic model
- Classification and regression tree
- Random forest
- Comparison test of mean and variance
- Clustering

