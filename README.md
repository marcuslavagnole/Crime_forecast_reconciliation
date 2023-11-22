Directory with data sets and R routines used in:
**Improving crime count forecasts in the city of Rio de Janeiro via reconciliation**, In preparation.

- **data_processing.R** : manipulate the raw data set in order to generate useful data objects for the base forecasts and reconciliation;
- **base_forecast.R** : MCMC routine for the weighted quantile regression based on the score likelihood;
- **reconciliation.R** : MCMC routine for the weighted quantile regression based on the approximate method.
- Directory **./data_base** contains the raw data set;
- Directory **./data_treated** contains data objects generated in **data_processing.R**.
