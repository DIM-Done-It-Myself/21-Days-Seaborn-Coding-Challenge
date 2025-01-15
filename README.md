# 21 Days Seaborn Coding Challenge

# SEABORN
Seaborn is a Python data visualization library built on top of Matplotlib. It provides a high-level interface for creating attractive and informative statistical graphics. Seaborn is widely used in data analysis and machine learning for visualizing data trends, distributions, and relationships between variables.

Key Features of Seaborn:
1.	Default Styles: Seaborn comes with aesthetically pleasing default styles that enhance the visual appeal of plots.
2.	Statistical Functions: It supports statistical plotting, including regression, distribution, and categorical plots.
3.	DataFrame Integration: Works seamlessly with pandas DataFrames, making it easy to create plots directly from your datasets.
4.	Built-in Themes: Offers themes like darkgrid, whitegrid, dark, white, and ticks for customizing the look of your plots.
5.	Complex Plots Made Simple: Simplifies the creation of complex visualizations like heatmaps, violin plots, and pair plots.
6.	Automatic Handling of Colors: Manages color palettes effectively, allowing for easy creation of visually distinct plots.

    
Commonly Used Functions in Seaborn:
1.	Distribution Plots:
o	sns.histplot(): Visualizes data distribution as a histogram.
o	sns.kdeplot(): Plots a kernel density estimate.
o	sns.boxplot(): Displays the distribution of data using a box plot.
2.	Relational Plots:
o	sns.scatterplot(): Creates a scatter plot for visualizing relationships between two variables.
o	sns.lineplot(): Plots a line chart.
3.	Categorical Plots:
o	sns.barplot(): Creates a bar chart with optional statistical aggregation.
o	sns.countplot(): Counts and plots occurrences of categorical variables.
o	sns.violinplot(): Displays the distribution of a numeric variable across categories.
4.	Matrix Plots:
o	sns.heatmap(): Visualizes data in matrix form, commonly used for correlation matrices.
5.	Pair Plots:
o	sns.pairplot(): Visualizes pairwise relationships in a dataset, especially useful for exploratory data analysis.
6.	Facet Grids:
o	sns.FacetGrid(): Maps plots to different subsets of data based on categorical variables.
Installation:
To install Seaborn, use pip:
pip install seaborn
Example:
Here’s a simple example to get started:
python

import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

# Sample data
data = sns.load_dataset("iris")

# Create a scatter plot
sns.scatterplot(data=data, x="sepal_length", y="sepal_width", hue="species")

# Display the plot
plt.show()

