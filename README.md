# Estimating_Crop_Evapotranspiration_Uncertainty_with_HRMET

![download](https://github.com/Kwakuopokuware401/Estimating_Crop_Evapotranspiration_Uncertainty_with_HRMET/assets/94206249/faccd35f-61ed-4b94-b142-e8b172c4c48b)


Author:  Kwaku Opoku-Ware (kwakuopokuware401@gmail.com)

# Description
This project implements the HRMET evapotranspiration model in Python and analyzes uncertainty in the model outputs.

# Overview
- Implements gridded HRMET model in Python based on original MATLAB code

- Generates synthetic weather data as model inputs

- Estimates uncertainty in inputs like temperature using statistical techniques

- Propagates input uncertainty through the HRMET model to estimate output uncertainty

- Analyzes and visualizes uncertainty maps

# Uncertainty Analysis

-Input uncertainty is estimated using statistical techniques like moving window standard deviation.

-Uncertainty is propagated through the HRMET model using Monte Carlo simulation.

-Output uncertainty metrics are analyzed.

## Requirements
The code requires the following Python packages:

-Python 3.6 or higher

-numpy

-matplotlib

-datetime

## Applications
Potential use cases for this modeling approach include:

-Spatial analysis of ET over agricultural fields

-ET forecasting for drought monitoring

-Hydrologic modeling of watersheds

-Quantifying uncertainty in hydrologic predictions

## References
The HRMET model, written in Matlab code, was originally developed by Sam Zipper (samzipper@ku.edu). If you utilize or adapt the HRMET model in your work, please cite the following paper to credit the original model developers:

    Zipper, S.C. & S.P. Loheide II (2014). Using evapotranspiration to
    assess drought sensitivity on a subfield scale with HRMET, a high
    resolution surface energy balance model. Agricultural & Forest
    Meteorology 197: 91-102. DOI: 10.1016/j.agrformet.2014.06.009

Link: http://dx.doi.org/10.1016/j.agrformet.2014.06.009

I appreciate you acknowledging the research contributions that enabled the development of HRMET. Citing relevant papers helps advance scientific progress through the open dissemination of knowledge. Please let me know if you have any questions about appropriately citing this model.
