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

# Python Package Installer(pip)

Python Package Installer(pip)
pip is the Python Package Installer. It’s a tool used to install and manage Python libraries and dependencies that are not part of the standard Python library. pip allows you to easily download and install packages from the Python Package Index (PyPI), as well as other package repositories.

Key Features of pip:

1.	Install Libraries: Install any Python library or package available on PyPI.
2.	Upgrade Packages: Update installed packages to their latest versions.
3.	Uninstall Packages: Remove packages that are no longer needed.
4.	List Installed Packages: View all Python libraries currently installed in your environment.
5.	Environment Compatibility: Works well with virtual environments, allowing for isolated package installations.
   
Basic pip Commands:

Here are some commonly used commands with examples:

    1.	Install a Package:
    pip install package_name
    Example:
    pip install seaborn

    2.	Upgrade a Package:
    pip install --upgrade package_name
    Example:
    pip install --upgrade seaborn

    3.	Uninstall a Package:
    pip uninstall package_name
    Example:
    pip uninstall seaborn

    4.	List Installed Packages:
    pip list

    5.	Check for Outdated Packages:
    pip list --outdated

    6.	Install a Specific Version:
    pip install package_name==version_number
    Example:
    pip install seaborn==0.11.2

    7.	Show Package Details:
    pip show package_name
    Example:
    pip show seaborn

    8.	Save Installed Packages to a File:
    pip freeze > requirements.txt

    9.	Install Packages from a File:
    pip install -r requirements.txt

Checking if pip is Installed:

To check if pip is installed, run:
pip --version

If it’s installed, you’ll see output like:

pip 23.0.1 from /usr/local/lib/python3.9/site-packages (python 3.9)

If pip is not installed, you can install it by downloading get-pip.py and running:

python get-pip.py

