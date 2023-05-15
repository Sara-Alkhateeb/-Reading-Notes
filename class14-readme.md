# class - 14
## What are the key differences between Matplotlib, Seaborn, and Bokeh libraries in terms of their features and use cases? Provide an example of a specific visualization that is more suitable for each library.

## Matplotlib:

Matplotlib is a versatile plotting library that provides a wide range of customizable plots and charts.

It offers low-level control over every aspect of a plot, allowing users to create complex visualizations.

`Example:` Visualizing a time series dataset with line plots and scatter plots.

## Seaborn:

Seaborn is built on top of Matplotlib and provides a higher-level interface for statistical data visualization.
It offers a set of attractive default styles and color palettes that make it easy to create visually appealing plots.
Seaborn focuses on statistical relationships and provides specialized functions for visualizing categorical and relational data.

`Example:` Visualizing the distribution of a numerical variable across different categories using a box plot or violin plot.

## Bokeh:

Bokeh is a library that targets interactive and browser-based visualizations, suitable for creating web applications and dashboards.
It allows for the creation of interactive plots that can respond to user interactions like zooming, panning, and hovering.
It emphasizes interactivity and provides tools for linking multiple plots and creating interactive widgets.

`Example:` Creating an interactive line plot with tooltips that display additional information when the user hovers over the data points.

## In the Seaborn library, what are the main functions to create relational, categorical, and distribution plots? Briefly explain the purpose of each type of plot and provide an example use case.

1. Relational Plots (sns.relplot()):

`Purpose:` Visualize the relationship between two numeric variables.

`Example Use Case: `Plotting the correlation between temperature and ice cream sales over time.

2. Categorical Plots (sns.catplot(), sns.boxplot(), sns.stripplot(), sns.barplot(), sns.countplot(), etc.):

`Purpose:` Visualize the distribution or relationship between a 

categorical variable and one or more numeric variables.

`Example Use Case:` Comparing average sales of different products using a bar plot or visualizing the distribution of student grades across different classes using a box plot.

3. Distribution Plots (sns.displot(), sns.histplot(), sns.kdeplot(), sns.rugplot(), etc.):

`Purpose:` Visualize the distribution of a single variable.

`Example Use Case: `Plotting the distribution of heights in a population using a histogram or visualizing the density estimate of exam scores using a kernel density plot.

## Discuss the role of the Seaborn Cheat Sheet in a Python developer’s workflow. What are some key sections or elements featured in the cheat sheet that can help a developer quickly reference Seaborn functionalities?
It provides quick access to key functionalities, plot types, customization options, and code examples. The cheat sheet includes sections on plotting functions, plot types with visual representations, customization elements like color palettes and annotations, statistical functions, and code snippets. Having the cheat sheet handy improves developers' efficiency and productivity by allowing them to quickly find the information they need without searching through extensive documentation.

`Plotting Functions:` The cheat sheet highlights the main plotting functions in Seaborn, such as `relplot()`, `catplot()`, `displot()`, and more.
