# Which parameters tend to have an effect on the renting duration of FordGoBikes?
## by Moritz Stabel


## Dataset

The dataset contains 453159 entries for bike bookings in the year 2017 in the Bay Area, starting in June, since this is earliest entry in the dataset. The attributes contain the renting duration, information about the user like birth year, gender and if the user is a subscriber or not, the datetime of the rental beginning and ending and the coordinates of the start and end station. 66,462 entries where removed from the dataset du to inconsistencies or missing information. 

## Summary of Findings: 

- With a logarithmic scale, a normal distribution could be assumed for the renting duration, with the median arround  10 minutes.

- The total number of bike rentals increases over the summer and decreases towards the winter

- There are more bookings under the week compared to the weekend, the distribution remains the same over the month and week days

- there are more younger people using the service 

- There are three times as many male users compared to female user 

- The number of subscribed users is 8 times higher than the number of customer users

- the average rental duration remains almost the same over the month, but increases towards the weekend compared to weekdays

- the number of subscribed users decreases towards the weekend, while the number of customer users increases towards the weekend

- in average a customer users rents a bike mor than twice as long as a subscribed user

- under the week, the most rentals happen during the rush hours, on the weekend the peak is arround midday


## Key Insights for Presentation

The presentation focuses on the duration of rentals and the influence of months and weekdays on it. 

To display the findings appropriate some slight conifgurations where made to the plots
- adding axis-titles and propper scaling
- changing ticks and ticklableing
- changing colormaps
- adding titles


## Resources
https://seaborn.pydata.org/generated/seaborn.FacetGrid.html
https://matplotlib.org/api/_as_gen/matplotlib.pyplot.hist.html
https://stackoverflow.com/questions/25394913/spacing-between-bars-in-matplotlib-hist-with-thousands-of-bins
Udacity-Code-Examples - Univariate Exploration of Data
Udacity-Code-Examples - Bivariate Exploration of Data
Udacity-Code-Examples - Multivariate Exploration of Data
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html
https://stackoverflow.com/questions/11041405/why-dict-getkey-instead-of-dictkey
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Timestamp.weekday.html
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DatetimeIndex.weekday.html
https://stackoverflow.com/questions/25212986/how-to-set-some-xlim-and-ylim-in-seaborn-lmplot-facetgrid
https://seaborn.pydata.org/generated/seaborn.FacetGrid.html
