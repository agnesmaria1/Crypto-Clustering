# Crypto-Clustering

This application assembling investment portfolios that are based on cryptocurrencies. Jupyter notebook that clusters cryptocurrencies by their performance in different time periods.

---

## Technologies

This project leverages python 3.7 with the following package:

* [Pandas](https://pandas.pydata.org/) - Entry point, open source data analysis and manipulation tool.

* [scikit-learn](https://scikit-learn.org/stable/) - Python machine learning that provides supervised and unsupervised learning algorithms.

* [hvPlot](https://hvplot.holoviz.org/) - Provides an alternative for the static plotting API provided by Pandas and other libraries.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---

## Usage

To use this machine learning application simply clone the repository and run the **ecrypto_investments.ipynb** with:

```python
  crypto_investments.ipynb
```

---

## Contributors

This project brought to you by Agnes.

---

## License
MIT License
