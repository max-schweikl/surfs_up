# Surfs Up Analysis

## Project Overview
The goal of this analysis is to see temperature statistics for Hawaii in both June and December, and decide if its sustainable to open and manage a surf shop yaer-round.  To run this analysis, we ran a query each for both June and December to pull back descriptive statistics (mean, standard deviation, quartiles, etc.).  Once ran, this data was converted over to a dataframe and then pulling the summary statistics back using Python code.  Below is what we found.

## Results

### June Summary Statistics

### December Summary Statistics

In reviewing both June and December summary statistics, the following conclusions can be drawn:
  1) The average temperature in June is 75 degrees, while in December the average temperature is 71 degrees.  This shows that the temperature, on average, was mostly similar between the two months.
  2) The maxmimum temperature in June was 85 degrees, while the maximum temperature in December was 83 degreees.  These are also strikingly similar.
  3) December saw a minimum temperature of 56 degrees, while in June the minimum was 64 degrees.  This is where we see the widest difference.  This can also be concluded further when we look at teh standard deviation for each time period, with December edging slightly higher at 3.74, compared to 3.25 for June.

## Summary
Overall, the weather patterns for both June and December are quite similar, and it could warrant having the shop open during either period.  However, if push comes to shove and one period must be picked over another, then June would be the better option, as they maintain a temperature minimum that is 8 degrees higher than December, as well as a standard deviation that is 0.49 smaller.

While temperature is one category to review, do we also understand other meteorlogical elements, including but not limited to historical wind speed, precipitation, humidity and so on?  One additional query we can run is the precipitation data for each period, as while it may be an ideal temperature day, higher average rainfall may still lead to less customer volume.  Another query is pulling in historical wind speed data, which could influence if there's enough wave volume to draw in surfers, and in return more prospective customers to the ice cream stand.  Based on location of the ice cream stand, we'll also want to ensure we're pulling in the weather station location that is within the cloesst proximity to the planned location, but also holds enough material weather data to draw conclusions.
