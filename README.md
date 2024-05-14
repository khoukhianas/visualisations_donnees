# visualisations_donnees
# Data Manipulation and Visualization Tool
This Python GUI application allows you to load and interact with CSV data. You can perform tasks like loading data, displaying statistics, 

showing histograms, and plotting scatter graphs based on the loaded dataset.

# Features
Load Data: Load CSV data file containing numerical data.

Display Statistics: View descriptive statistics of the loaded dataset.

Histogram Display: Visualize the distribution of selected columns using histograms.

Scatter Plot: Plot scatter graphs of selected column pairs.

# Prerequisites

Python 3.x

tkinter library (standard with Python)

pandas library (pip install pandas)

numpy library (pip install numpy)

matplotlib library (pip install matplotlib)

# Installation

Clone or download the data_visualizer.py script.

Install required dependencies using pip:


pip install pandas numpy matplotlib

Open a terminal or command prompt.

Navigate to the directory containing data_visualizer.py.

Run the script using:

python data_visualizer.py
# Usage
Load Data:

Click "Charger des données" to select a CSV file.

The selected file will be loaded into the application.

Display Statistics:

Click "Afficher les statistiques" to view descriptive statistics of the loaded dataset.

Statistics include count, mean, standard deviation, minimum, quartiles, and maximum.

Histogram Display:

Select a column from the dropdown menu.

Click "Afficher l'histogramme" to visualize the distribution of the selected column.

Scatter Plot:

Select two columns from the dropdown menus.

Click "Afficher le graphique" to plot a scatter graph of the selected column pairs.

# Notes
Ensure the CSV file contains numerical data for proper analysis.

Descriptive statistics are computed using pandas.

Histograms and scatter plots are generated using matplotlib.
