# Bitcoin Arbitrage Analysis:
`A study of 2018 price action on two popular exchanges`

---

## Description

Using `pandas` tools and Jupyter notebook, this project retrospectively analyzes Bitcoin arbitrage opportunities between two popular cryptocurrency exchanges, Coinbase and Bitstamp. The analysis specifically focuses on three days during the first three months of 2018: one early on (Jan 28), one in the middle (Feb 6), and one at the end (Mar 16). First, I collected necessary information by using `pathlib` to import 2018 price data and organized it into a DataFrame for analysis. Next, I prepared the data by dropping NaN and duplicated values, removing unwanted symbols, and converting data types to `float`. Finally, I analyzed the data by generating summary statistics and graphs and then calculated net profitable trades and cumulative profits for each day in the study.

Analysis can be found throughout the notebook in markdown code, especially after graphs or important DataFrame comparisons.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For reading data into a DataFrame.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - For generating a file path to a CSV.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install mkdocs
```

---

## Usage

To use the Bitcoin arbitrage analysis code:

1. Locally clone the BTC_arbitrage_analysis repository from GitHub using the following link:

```python
git clone https://github.com/elliotlozano/BTC_arbitrage_analysis.git
```

2. Run the [crypto_arbitrage](crypto_arbitrage.ipynb) program.

3. Examine the graphs and review the commentary describing the significance of the results.

---

## Contributors

Elliot Lozano

[E-mail](elliotlozano95@gmail.com)

---

## License

MIT