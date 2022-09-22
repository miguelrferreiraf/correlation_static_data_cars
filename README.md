# Analysing correlation between data features

## Basic data science

<div align="center"><img src=data_image/vector-cars-collection-vehicles-flat-style_1284-44161.jpg width=50%></div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

Hey, folks!

What about some basic data science? In this small simple projects I demonstrate one of the basic concepts of data science, the correlation coefficient or Pearson correlation.

There are also some important line codes involving data cleaning that I think is very very important. Don't ignore it.

Concepts approached by this code includes:

### Distribution

Basic concept involving the amount of data from a specific feature for another specific feature:

```
#distribution plot
sns.FacetGrid(data,height=5).map(sns.histplot,"height").add_legend()
```

<div align="center"><img src=data_image/distribution_plot.png></div>

### Distribution through boxplot

<div align="center"><img src=data_image/boxplot_car_price.png></div>

<div align="center"><img src=data_image/boxplot_to_distribution_price_drivewheels.png></div>

### Multivariate analysis

Consists in a analysis of several correlations; usually we define by multivariate when it's made with more than two variables.

<div align="center"><img src=data_image/matrix_scatter_plot_columns.png></div>

### Correlation coefficient

Finnaly, the correlation coefficient allow us to plot all correlation among all features. 

<div align="center"><img src=data_image/correlation_heatmap.PNG></div>
