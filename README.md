# vizit Package

This package, built on top of Numpy, Pandas, Matplotlib, and Seaborn, allows the user to quickly create data visualizations. These visualizations are more exploratory in nature, but explanatory charts can also be created. The user can plot one or two variables using any combination of categorical and numerical variables. The following visualizations can be created:

- One categorical variable: bar chart, pie chart, waffle chart
- One numerical variable: histogram
- Two categorical variables: clustered bar chart, heatmap, stacked bar chart
- One categorical variable and one numerical variable: violin chart, box chart, faceted histograms, bar chart, point plot
- Two numerical variables: scatter plot, heatmap, weighted histogram, point plot

# Files

- Generalviz.py: Parent class for creating visualizations
- Onedimension.py: Contains the Cat and Num classes for creating one-dimensional visualizations
- Twodimension.py: Contains the CatCat, CatNum, and NumNum classes for creating two-dimensional visualizations
- __init__.py: Defines code to run when vizit package is imported

# Installation

To install this package from PyPI, execute the following in the command line:

```
$ pip install vizit
```