# 5-day-forecast-ML-Pipeline
5-day movement forecast results from a combination of alpha factors, leveraging Ada-booster classification library.
Binary forecasts (only direction) are computed daily as results of the ML (Ada-booster classification) model that runs within the quantopian pipeline every night. However, model is only trained every 'Monday' (Configurable to any other day in the week).
