# Minimum Viable Consulting

# Analysis of the Film Industry

I used a linear regression model to describe Box Office Total Domestic Gross as a function of the Number of Theaters, Budget and Runtime of the Movie.

The figures below show observed values of the Domestic Total Gross (in blue) compared to
predicted values of the Domestic Total Gross (in yellow) as a function of:

(i) Number of Theaters, more specifically, Exp(Number of Theaters/1000),
![gross_vs_theaters](/figs/gross_vs_theaters.png)

(ii) Budget of the Movie (in $) and
![gross_vs_budget](/figs/gross_vs_budget.png)

(iii) Runtime of the Movie (in mins)
![gross_vs_runtime](/figs/gross_vs_runtime.png)

The model captures the main features of the observed values of Domestic Total Gross. In particular, there is a gross linear relation between the Domestic Total Gross and Exp(Number of Theaters) that is depicted in the first figure above. Adjusted R-squared of the model is 0.65. The distribution of the errors, that is observed - predicted Domestic Total Gross, is shown below:
![prediction errors](/figs/errors.png)
