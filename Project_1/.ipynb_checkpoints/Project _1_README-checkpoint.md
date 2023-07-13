# <center>Project 1: Data Analysis of Singapore Rainfall, Surface Air Temperature<br> and its impact on local seafood production</center>
## Introduction

In the face of unpredictable geopolitical environmental, Singapore aims to increase its food resilience by increasing local food supply to 30% by 2030. As climate change causes irregular rainfall patterns and increased temperatures globally, Singapore is not spared. In addition, studies have shown that increasing temperatures and decreasing seawater salinity due to global warming such as increased rainfall and ice cap melting leads to detrimental effects on marine organisms. Hence, these environmental factors could potentially affect Singapore's local seafood production.

## Problem Statement
Singapore's surface air temperature and rainfall pattern could affect the amount of local seafood production.

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|month|datetime|seafood-supply-and-wholesale|every month from 2002 to may 2022| 
|seafood_catch|float|seafood-supply-and-wholesale|amount of seafood caught from Singapore waters in Tonnes| 
|imports_of_seafood|float|seafood-supply-and-wholesale|amount of seafood imported by Singapore in Tonnes|
|exports_of_seafood|float|seafood-supply-and-wholesale|amount of seafood exported from Singapore in Tonnes| 
|total_rainfall|float|rainfall-monthly-total|total monthly rainfall in mm| 
|month_mean_temp|float|surface-air-temperature-monthly-mean-daily-minimum|mean monthly surface air temperature in °C| 


## Analysis Summary
The amount of seafood caught from Singapore's waters was observed to decrease as air surface temperature increases above 25.4°C. Total rainfall above 250mm was also observed to have decreasing seafood catch. Over the past 10 years (from 2012 onwards), it was found that the mean surface air temperature has increased from 24.96°C to 25.39°C and total rainfall decreased from 189.1mm to 162.13mm. In addition, the quantity of seafood catch in Singapore was found to have decreased by 46.29% (10,475 Tonnes) in the last 10 years. This further highlights the importance of Singapore being food resilient to reduce dependency on food imports.

## Conclusions and Recommendations 
There does not seem to be any clear relationship between surface air temperature, total rainfall versus seafood catch. To help us better understand the relationship between these measurements, we can consider collecting the following measurements:
<ul>
    <li>Amount of seafood produced by Singapore's fisheries
        <ul>
            <li>This will help us to better understand if local climate change will affect local seafood production. This is because environmental conditions in fisheries are more controlled as compared to the wild.</li>
        </ul>
    </li>
    <li>
        Seawater chemical parameters (e.g., salinity, dissolved carbon dioxide concentration etc.) after a heavy rainfall or during a dry season
        <ul>
            <li>This will help to establish if changes in surface air temperature or heavy rainfall would significantly affect seafood catch as these chemical parameters are known to negatively affect physiology of marine creatures.</li>
        </ul>
    </li>
</ul>