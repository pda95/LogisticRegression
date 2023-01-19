### Dataset Description: ###
This dataset contains about 10 years of daily weather observations from many locations across Australia.<br />
RainTomorrow is the target variable to predict. It means, Did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.<br />

### Task: ###
We should predict next-day rain by training classification models on the target variable RainTomorrow.<br />

### Dataset Attributes: ###
**Date**: the date of observation

**Location**: the common name of the location of the weather station

**MinTemp**: the minimum temperature in degrees celsius

**MaxTemp**: the maximum temperature in degrees celsius

**Rainfall**: the amount of rainfall recorded for the day in mm

**Evaporation**: the so-called Class A pan evaporation (mm) in the 24 hours to 9am

**Sunshine** :the number of hours of bright sunshine in the day.

**WindGustDir**: the direction of the strongest wind gust in the 24 hours to midnight

**WindGustSpeed**: the speed (km/h) of the strongest wind gust in the 24 hours to midnight

**WindDir9am**: direction of the wind at 9am

**WindDir3pm**: direction of the wind at 3pm

**WindSpeed9am**: wind speed (km/hr) averaged over 10 minutes prior to 9am

**WindSpeed3pm**: wind speed (km/hr) averaged over 10 minutes prior to 3pm

**Humidity9am**: Humidity (percent) at 9am

**Humidity3pm**: humidity (percent) at 3pm

**Pressure9am**: atmospheric pressure (hpa) reduced to mean sea level at 9am

**Pressure3pm**: atmospheric pressure (hpa) reduced to mean sea level at 3pm

**Cloud9am**: fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.

**Cloud3pm**: fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values

**Temp9am**: temperature (degrees C) at 9am

**Temp3pm**: temperature (degrees C) at 3pm

**RainToday**: boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0

**RainTomorrow**: the amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".
