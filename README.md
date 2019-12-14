# Physionet-Cardiology-Challenge-2012

https://physionet.org/content/challenge-2012/1.0.0/

The focus of the PhysioNet/CinC Challenge 2012 is to develop methods for patient-specific prediction of in-hospital mortality. Participants will use information collected during the first two days of an ICU stay to predict which patients survive their hospitalizations, and which patients do not.

## Problem

To predict per patient:
1. In-hospital mortality (1: will die, 0: will not die) - Classification
2. Length of Stay (LoS) (# days in hospital) - Regression

## Data

* [Raw Data](https://github.com/Msundarv/Physionet-Cardiology-Challenge-2012/blob/master/Project_Data.zip)
* [Viz Data](https://github.com/Msundarv/Physionet-Cardiology-Challenge-2012/blob/master/Prep_Data/Viz_Data.zip) - Data prepared for exploratory analysis by [Viz_Data_Pipe.ipynb](https://github.com/Msundarv/Physionet-Cardiology-Challenge-2012/blob/master/Viz_Data_Pipe.ipynb)
* [Prep Data](https://github.com/Msundarv/Physionet-Cardiology-Challenge-2012/tree/master/Prep_Data) - Data prepared for modelling by [Data_Prep_Pipe.ipynb](https://github.com/Msundarv/Physionet-Cardiology-Challenge-2012/blob/master/Data_Prep_Pipe.ipynb)

## Visualization

[Link](https://public.tableau.com/profile/sundar.v2621#!/vizhome/PhysioNet/Dashboard1) to Tableau Dashboard used for exploration.

## Best Model's Metric


| Model        | Metric        | 
| ------------- |:-------------:|
| Mortality Classifier     | 0.84 (AUC)|
| LoS Regressor      | 11.46 (RMSE)     | 

## Authors

- [Sundar V](http://msundarv.com/)
- [Mahendren Sundararajan](https://www.linkedin.com/in/mahendrens)
- [Gogula Krishnan](https://sg.linkedin.com/in/gogulak)
