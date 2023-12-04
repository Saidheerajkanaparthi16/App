# EDA web App

Exploratory Data Analysis (EDA) Web App
Abstract
The EDA Web App is a data analysis tool designed to provide users with an intuitive interface for uploading, analyzing, and visualizing datasets. The main purpose of the project was to simplify the exploratory data analysis process by automating common tasks such as statistical summary generation, correlation analysis, and data visualization. As a result, users can obtain insights from their data quickly and interactively, making the app a useful asset for researchers, data scientists, and students.

Data Description:
The data handled by the EDA Web App can come from a variety of sources, as long as it is in CSV format. The web app is equipped to process datasets with numeric, categorical, and text data, offering a suite of preprocessing steps to clean and prepare the data for analysis. This includes handling missing values, converting data types, and filtering relevant features for visualization and statistical analysis.

Algorithm Description:
The web app employs several algorithms and processes to conduct EDA:

Descriptive Statistics: Calculates mean, median, mode, standard deviation, and other summary statistics.
Correlation Heatmap: Generates a heatmap representing the Pearson correlation coefficients between numerical features in the dataset.
Visualization Algorithms: Depending on the user's choice, the app can create bar plots, histograms, scatter plots, and more using the Seaborn and Matplotlib libraries.
Statistical Tests: Performs Pearson correlation tests and other statistical tests where applicable.

Tools Used:
Python: The primary programming language used for backend development.
Streamlit: Serves as the framework for creating the web app interface, handling file uploads, user interactions, and rendering visualizations.
Pandas: Utilized for data manipulation and cleaning tasks.
Seaborn and Matplotlib: These libraries are used to generate various statistical plots and charts for data visualization.
NumPy: Assists in numerical operations and serves as the backbone for Pandas and data manipulation.
SciPy: Provides functions for performing statistical tests.
Virtualenv: Used to create an isolated Python environment for managing project dependencies.
