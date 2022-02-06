# Rental Analysis

The Rental Analysis application provides an all-in-one tool used to analyze housing rental markets and locate properties for potential potential investment opportunities. The application specifically will demonstrate analysis of the San Francisco market using key real estate data.   

The application calculates housing units per year, average sale prices per square foot, and average sale prices by neighborhood, in addition to using visualization tools to visualize the calculated results and identify relationships and patterns in the sets of real-estate data. 

---

## Technologies

This application leverages Python 3.7 with the following libraries and dependencies: 

Pandas: Python library for data analysis and manipulation

Pathlib: Python filesystem module

PyViz: Pandas data visualization package

---

## Installation Guide

Pandas is included in the Anaconda open source distribution. You may download Anaconda for your operating system here: https://www.anaconda.com/products/individual. After installing Anaconda, follow the Pandas installation instructions here: https://pandas.pydata.org/getting_started.html. 

Install the pathlib module using the pip command: pip install pathlib 

PyViz is a Python data visualization package that holds the hyplot and geoviews libraries that are used in this application. Install PyViz by logging into your Conda dev environment. The conda install command for PyViz and the hvplot and geoviews libraries is: 
conda install -c pyviz hvplot geoviews.

Confirm the packages are installed by runnning the commands below:
conda list hvplot
conda list geoviews

---

## Usage

To use the Rental Analysis application, clone the repository and run the san_francisco_housing.ipynb file.

---

## Contributors

Contributions by Carl Frederick.

---

## License

MIT.