# CMPE255-Bike-Sharing-Washington-DC
## Project Members:
| Project Members | GitHub-Profile-Link | 
| ----- | ----- |
| Niranjan Reddy Masapeta | https://github.com/Neeraj-MSSJ |
| Purna Sai Mahesh Goud Palagani | https://github.com/Maheshpalagani78 |
| Sujan Rao Chikkela |https://github.com/sujanchikkela |
| Utsav Savaliya | https://github.com/utsavsavaliya |
## Collaboration Plan:
-          To coordinate at regular intervals and discuss action plans.
-          Zoom meeting and SJSU Gmail will be our preferred mode of communication.
-          We plan to use GitHub repository for code collaboration purposes.
## Main Goal Statement:
Using past usage patterns for bike rentals, to forecast demand for bike rental services in future.
Project Objectives:
Apply various ML techniques for forecasting and compare the performances of models.

## Dataset:
<details><summary>Click to view Dataset</summary>

  | Attributes | Description |
| ----- | ----- |
| Date | date format is entered as YYYY-MM-DD |
| temp_avg | Average daily temparature is recorded in degree celsius |
| temp_min | Min daily temparature is recorded in degree celsius |
| temp_max | Max daily temparature is recorded in degree celsius |
| temp_observ | temperature at the time of observation in degree Celsius |  
| precip | Amount of preciption recorded in  mm |
| wind | wind speed in m/s |
| wt_fog | type of fog, ice fog, or freezing fog |
| wt_heavy_fog | weather type heavy fog or heaving freezing fog |
| wt_thunder | weather type thunder |
| wt_sleet | weather type ice pellets, sleet, snow pellets |
| wt_hail | weather type hail |
| wt_glaze | weather type glaze or rime |
| wt_haze | weather type smoke or haze |
| wt_drift_snow | weather type blowing or drifting snow |
| wt_high_wind | weather type high or damaging winds |
| wt_mist | weather type mist |
| wt_drizzle | weather type drizzle |
| wt_rain | weather type rain (may include freezing rain, drizzle, and freezing drizzle) |
| wt_freeze_rain | weather type freezing rain |
| wt_snow | weather type snow, snow pellets, snow grains, or ice crystals |
| wt_ground_fog | weather type ground fog |
| wt_ice_fog | weather type ice fog or freezing fog |
| wt_freeze_drizzle | weather type freezing drizzle |
| wt_unknown |  weather type unknown source of precipitation |
| casual | number of unregistered customers |
| registered | number of registered customers |
| total_cust |  sum of registered and casual customers |
| holiday | indicates whether the day is a holiday or not |
  </details>
  
## Dataset Summary:
The given dataset contains the data collected on each day from 2011 to 2018. Each row in the dataset represents a day and columns represent the attributes recorded for that particular day. It is a continuous time-series data. temp_avg, temp_max, temp_min and temp_observ has data related to the temperature attributes on that particular day for each record. precip is the precipitation and wind is the wind speed observed at the point of observation. All the wt_ attributes describes the weather details on that day: for example, a value of 0 in wt_rain and 1 in wt_fog means no rain on that day and fog is present on that day. casual users are the ones who are not registered on the application and registered are the registered customers. Our target variable in the dataset is total_cust which is the summation of casual and registered users. We are trying to forecast the total_cust value to get an estimate about the demand of bicycles so we can make necessary arrangements. holiday flag indicates whether the day is a holiday or not.

## Dataset Source:
https://www.openml.org/search?type=data&status=active&id=43486&sort=runs
