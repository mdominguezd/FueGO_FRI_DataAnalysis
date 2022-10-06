# FueGO FireRiskIndex DataAnalysis

In this repository the data collection and analysis for the FueGO app is explained

The jupyternotebook is divided into two parts:
1. Meteorological data collection

Meteorological data was retrieved from MeteoGalicia's website as a JSON file.

2. Linear regression analysis

The weights for each parameter in the index calculation were decided base on the information given by a regression model fitted between Burned Area and the average parameters in municipalities. Higher weights were given to more significant parameters in the regression.

$$ BurnedArea = \beta \cdot MeteoParams $$
