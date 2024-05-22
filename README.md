# WINE QUALITY PREDICTION
Use a dataset containing wine features to predict the quality of the wine

* This project is a part of my internship at **TechnoHacks Edutech** 

## Dataset Information
These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

Input variables (based on physicochemical tests):

| Column |  Description                       |
| :-------- |  :-------------------------------- |
| **Fixed acidity**      |  most acids involved with wine or fixed or nonvolatile (do not evaporate readily) |
| **Volatile acidity**      |  the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste |
| **Citric acid**      |  found in small quantities, citric acid can add 'freshness' and flavor to wines |
| **Residual sugar**      |  the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet |
| **Chlorides**      |  the amount of salt in the wine |
| **Free sulfur dioxide**      |  the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine |
| **Total sulfur dioxide**      |  amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine |
| **Density**      |  the density of water is close to that of water depending on the percent alcohol and sugar content |
| **pH**      |  describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale |
| **Sulphates**      |  a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant |
| **Alcohol**      |  a standard measure of how much alcohol (ethanol) there is within a given volume of the drink, in percentage terms |

Output variable (based on sensory data):
* Quality (score between 0 and 10)

## Algorithms
* Logistic Regression
* K Neighbors Classifier
* Suport Vector Classification
* Random Forest Classifiier
* Decision Tree Classifier

**Best Model Accuracy : 90.3125**

![Model Screenshot](https://drive.google.com/uc?id=1j62XEnS32EylcwZI2WVrrR_xj3Yf4_L5)
