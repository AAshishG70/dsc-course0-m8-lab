# Aviation Accident Analysis

We prepared the airplane dataframe for the analysis as per the clients' need which highlights the following: 
 - airplane makes/models that are professional builds
 - airplanes with max lifetime of 40 years for a make/model retirement (i.e., from 1983 onwards)
 - separate recommendations for small aircraft vs. larger passenger models

 Based on the Airplane dataframe, we conducted various EDA i.e. Exploratory Data Analysis using the different visualization techniques and statistical measure.

 We separated out the dataframe for the small vs. the large planes and performed the statistical measure i.e. mean in our case to evaluate the lowest mean for the fatal/ serious injured fraction. With sorting, it provided us with the top 15 small as well as large plane category by make with the lowest mean. 

- We identified the 15 makes with the lowest mean serious/fatal injury fractions separately for small and large aircraft.
- Similar to injury risk, we found 15 makes with the lowest average aircraft destruction rates in each group.
- In Conclusion, from the analysis we have the make Airbus Industrie for the small and Aero Commander, Dehavilland and Swearinggen for the large airplane with low/ null Destroyed and Fatal/Serious Injury Fraction.

From the evaluation within the specific Airplane Types: 
1. Small Airplane Models
    - The mean fatal/seriously injured fraction for small planes shows that a subset of models consistently achieve lower injury rates.

    - The violinplot distribution reveals these safer models generally have tight distributions around low injury fractions, indicating consistent safety performance.

2. Large Airplane Models
    - For larger planes, the mean injury fractions are generally higher than small planes, reflecting the greater complexity and operational risks of larger aircraft.

    - The injury fraction distributions across large-plane models are wider and more variable, as shown in the violinplots.

Lastly, we looked into two other variables that causes the aircraft damages and injury 'Weather.Condition' and 'Broad.phase.of.flight'