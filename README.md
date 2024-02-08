# Temporal_Variogram_2023
## Created this repo for genrating temporal variograms for timeseries data
-- Variograms can be used in time series analysis with high resolution to find the time period beyond which the correlation stops.
-- This is significant because we can use this idea to resolve the time series to find the most minimal variation within the time series.
-- Hence the smallest time period for measuring this can be increased byond the current resolution.
-- This is highly useful in sensing applications where we monitor an environment every second or every microsecond for a variation.
-- But this can be resoved even with a lower resolution of few second may be even minutes hence saving the cost and power associated with sensing.
-- I have used this method to resolve the second-wise data of PM2.5 that we measure in a neighbourhood of the Dallas Fortworth Metroplex. 
-- The study indicated that instead of measuring the data every second of that particular day its better to mesure it every 12 seconds of the day. Hence saving the battery life of the sensor

## Important Note: This value is dependent on the sensing environemnt
