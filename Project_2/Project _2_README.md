# <center>Project 2: Features affecting price of resale HDB flats in Singapore</center>
## Introduction
In a land scarce Singapore, housing prices are expensive with some resale HDB flats fetching prices for up to a million dollars. In addition, the supply-demand imbalances for HDB flats further drives the prices of resale flats. Despite government efforts to moderate resale prices of HDB flats by implementing cooling measures, the prices are still increasing. This makes it a lucrative market. There are many plausible factors that could influence the property prices of HDB flats which we are interested to explore.

## Problem Statement
From the perspective of a property agent, we are interested in investigating factors that affects the prices of HDB resale flats so that we can maximise our profits.

## Model Selection and Results Summary
Three regression models were generated to compare and decide which model to use for the prediction of resale HDB price.
<ol>
    <li>Linear Regression</li>
    <li>Ridge Regression</li>
    <li>LASSO Regression</li>
</ol>

To determine which model to use, the difference in RMSE between the train and test datasets were compared. RMSE, it is an absolute measure of fit and it is in the same units as resale price. Hence, RMSE is the measure selected to determine which model to use. The lowest difference RMSE in was used for predicting resale prices of HDB.

The LASSO regression model was selected as it has the lowest difference in RMSE (0.367%) and the lowest test RMSE (51,783). The LASSO regression model minimizes overfitting by penalising the coefficients of the features. It shrinks the coefficients of irrelevant features to 0 which makes it easier to interpret.


## Conclusions and Recommendations 
It seems that HDB located near features that brings about convenience to the lives of people would fetch a higher resale value. Depending on the target audience, we can recommend HDB flats located near certain facilities to increase and optimise the success of our HDB sales. For instance, for couples with young children, we can recommend HDB flats near primary schools. 

Further studies can include the following to better evaluate the features affecting resale prices of HDB:

<ul>
    <li>Explore multicollinearity between the features as some of them might potentially be related to each other</li>
    <li>Collection of more data
    <ul>
        <li>Collect data related to demographics of buyers</li>
        <li>Location of other educational institutions such ITE, Polytechnics and Universities</li>
        <li>Location of healthcare facilities (e.g., Hospitals, Polyclinics etc.)</li>
        <li>Location of playgrounds, child/student care centre, community centres etc.</li>
    </ul>
    </li>
</ul>