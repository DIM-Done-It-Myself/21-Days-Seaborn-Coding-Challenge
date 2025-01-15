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
2.	Relational Plots:
3.	Categorical Plots:
4.	Matrix Plots:
5.	Pair Plots:
6.	Facet Grids:

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

