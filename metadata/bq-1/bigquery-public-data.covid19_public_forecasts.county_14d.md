# `covid19_public_forecasts.county_14d`
`bigquery`| `bigquery-public-data`
This predicts the value for key metrics for COVID-19 impacts over a 14-day horizon at the US state level.

## Column details
* [STRING]    `county_fips_code`
  - 5-digit unique identifer of the county.
* [STRING]    `county_name`
  - Full text name of the county
* [STRING]    `state_name`
  - Full text name of the state in which a given county lies
* [DATE]      `forecast_date`
  - Date of the forecast
* [DATE]      `prediction_date`
  - Predicted date of the given metrics
* [FLOAT]     `new_confirmed`
  - Predicted number of new confirmed cases on the prediction_date. This is not cumulative over time
* [FLOAT]     `cumulative_confirmed`
  - Predicted number of cumulative deaths on the prediction_date. This is cumulative over time
* [FLOAT]     `new_deaths`
  - Predicted number of new deaths on the prediction_date. This is cumulative over time
* [FLOAT]     `cumulative_deaths`
  - Predicted number of cumulative confirmed cases on the prediction_date. This is not cumulative over time
* [FLOAT]     `hospitalized_patients`
  - Predicted number of people hospitalized on the prediction_date. This is not cumulative over time
* [FLOAT]     `recovered`
  - Predicted number of people documented as recovered on the prediction_date. This is not cumulative over time
* [FLOAT]     `new_confirmed_ground_truth`
  - Actual number of new confirmed cases according to the ground truth data. This is not cumulative over time
* [FLOAT]     `cumulative_confirmed_ground_truth`
  - Actual number of cumulative confirmed cases according to the ground truth data. This is cumulative over time
* [FLOAT]     `new_deaths_ground_truth`
  - Actual number of new deaths according to the ground truth data. This is not cumulative over time
* [FLOAT]     `cumulative_deaths_ground_truth`
  - Actual number of cumulative deaths according to the ground truth data. This is cumulative over time
* [FLOAT]     `hospitalized_patients_ground_truth`
  - Actual number of people hospitalized according to the ground truth data. This is not cumulative over time
* [FLOAT]     `recovered_documented_ground_truth`
  - Actual number of people hospitalized according to the ground truth data

-------------------------------------------------------------------------------
*Do not make edits above this line.*
