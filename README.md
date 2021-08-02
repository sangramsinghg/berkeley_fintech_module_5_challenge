# A Financial Planner for Emergencies and Retirement

A Financial planner to evalute the financial health of a user. 

There are two tools:
1. Financial Planner for emergencies - visualize the current investments to see if there are enough emergency funds.
2. Financial Planner for retirement - forecase the performance of the retirement funds in 10 and 30 years.

This tool uses the .env file to retrieve the ALPACA API KEYS and uses them to retrieve historical price data. 
The price data is used in Monte Carlo Simulations to forecast the performance of the retirement fund.

---

## Technologies

This project uses python 3.7 along with the following packages:

* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - Web based user interface for data analysis.

* [pandas](https://github.com/pandas-dev/pandas) - Data analysis and manipulation library.

* [dotenv](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables.

* [alpaca-trade-api](https://pypi.org/project/alpaca-trade-api/) - alpaca-trade-api-python is a python library for the Alpaca Commission Free Trading API. It allows rapid trading algo development easily, with support for both REST and streaming data interfaces.

* [matplotlib](https://github.com/matplotlib/matplotlib) - Library for creating visualization in Python.

---

## Installation Guide

Please install the following before starting the application

```python
  pip install jupyterlab
  pip install pandas
  pip install dotenv
  pip install alpaca-trade-api
  pip install matplotlib
```
In case of issues, please see the requirements.txt for a complete list of packages with versions needed to run this application

---

## Usage

To use the financial planning tools, please download and open the **financial_planning_tools.ipynb** in jupyter lab after executing
the following on the command line:

```python
jupyter lab
```
Jupytper Lab should open automatically in a browser. 
If it does not, please follow the instructions on the command line.

---

## Contributors

Sangram Singh (sangramsinghg@yahoo.com)

---

## License

MIT