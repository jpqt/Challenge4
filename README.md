# Analyzing Portfolio Risk and Return
Assuming the role of a Quantitative Analyst for a investing platform we are aiming to offer our clients a seemless one stop for shop for retirement portfolios.

Worked on through Jupiter Labs

## Technologies

The project leverages Jupyter Notebook packaged with Anaconda, with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entry-point.

* [pathlib](https://github.com/nemec/pathlib) - Path manipulation library for .Net

* [csv](https://github.com/thephpleague/csv) - Csv is a library to ease parsing, writing and filtering CSV in PHP.

* [matplotlib](https://github.com/matplotlib/matplotlib) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

* [numpy](https://github.com/numpy/numpy) - NumPy is a community-driven open source project developed by a diverse group of contributors. The NumPy leadership has made a strong commitment to creating an open, inclusive, and positive community.


## Installation Guide

Clone GitHub Respoitories to your local machine

```sh
   git clone https://github.com/jpqt/Challenge4.git
 ```


## Usage
Import Data using read_csv function, then we analyze the portfolios performance with Pandas. 

Using Plot function to visualize the daily return data, cumprod function to calculate the cumulative returns and thus plotting the data again to visualize the data thus again. 

After we analyze the performance we Analyze the colatility once again with the plot function and the 'kind=box' parameter to visualize the data for the 4 portfolios and the S&P500. 

Then we Analyze the risk of each portfolio using 'std' function (standard deviation). 

Lastly we analyze the Risk-Return Profile on these portfolios and compare them to the S&P500 with the Sharp Ratio and we visualize the data and determine which offers the worst risk.


## Contributers

Name: Joshua Pak

E-Mail: taehanpak9@du.bootcamp.edu

## License
DU 2022