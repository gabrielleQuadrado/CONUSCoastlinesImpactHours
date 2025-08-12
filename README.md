# Assessing Impact Hours on Sandy Beaches - Data Release
Data release to the paper "Rising Impact Hours on Sandy Beaches Linked to Total Water Level Variability along U.S. Coastlines".

The data provided in this repository are used to reproduce the figures in the paper and include: 

1) [Annual Impact Hours per Regime](impactHoursbyRegime) - data for Figures 2, 3, 4 and 5. This dataset contains annual total water level (TWL) impact hours in the Storm Impact Scale Regimes swash, collision, overtopping, and inundation, from 1980 through 2021, along the U.S. Pacific (from Neah Bay, WA, to La Jolla, CA), Gulf (from Port Isabel, TX, to Naples, FL) and Atlantic coastlines (from Sandy Hook, NJ, to Fernandina Beach, FL). Each station has an individual "hoursPerYear_allregimes_stationname.mat" file. This file contains a 8 x n matrix, where n is the number of years with at least ≥80% hourly completeness, from 1980 through 2021. Rows represent the following:
  - Row 1: average swash impact hours per year
  - Row 2: standard deviation of swash impact hours per year
  - Row 3: average collision impact hours per year
  - Row 4: standard deviation of collision impact hours per year
  - Row 5: average overtopping impact hours per year
  - Row 6: standard deviation of overtopping impact hours per year
  - Row 7: average inundation impact hours per year
  - Row 8: standard deviation of inundation impact hours per year
    
_Averages and standard deviations are computed across beach profiles located within the same 30 km-long coastal segment, as defined in the paper.__

The folder also includes 'remainingYears_stationname.mat' files, which provide a vector listing the years with at least ≥80% hourly completeness for that station.

2) [Linear Trends in TWL Impact Hours](trendsSensSlope) - data for Figures 6 and 7. This dataset contains the Sen’s slope values and corresponding p-values for linear trends in TWL impact hours across the four Storm Impact Scale regimes swash, collision, overtopping, and inundation, from 1980 through 2021. The data are provided in a single Excel file 'trendsSensSlope.xlsx'. Columns represent the following:
   - ID: station ID number (matches the paper)
   - location: station name and state abbreviation
   - swash: Sen’s slope for swash impact hours/year
   - collision: Sen’s slope for collision impact hours/year
   - overtopping: Sen’s slope for overtopping impact hours/year
   - inundation: Sen’s slope for inundation impact hours/year
   - pvalue swash: p-value for swash trend significance
   - pvalue collision: p-value for collision trend significance
   - pvalue overtop: p-value for overtopping trend significance
   - pvalue inundation: p-value for inundation trend significance

   _Trend calculations are based on annual impact hours averaged across beach profiles located within the same 30-km long coastal segment, as defined in the paper._


