Notes on data and feature engineering: 

1. for periodic variables, like time of the day or month of the year, apply a decomposition like y = A * sin(2π * hour / 24) + B * cos(2π * hour / 24). This way one feature is broken into two linearly independent features. (careful about autocorrelation and feature independence)
