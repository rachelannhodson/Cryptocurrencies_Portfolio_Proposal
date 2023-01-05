# Cryptocurrencies_Portfolio_Proposal

This is a JupyterLab notebook which utilizes Python and scikit-learn to analyze and group investment data. A data analyst may use pandas to read a given `.csv` file then use the writen code to determine the best grouping for this data by way of KMeans.

---

## Technologies

Please be sure you have Jupyter Lab installed:

* [JupyterLab](https://jupyter.org/)

This application was written in Python 3.9.12. This application is dependent on the following libraries:

* [pandas](https://pandas.pydata.org/)
* [pyviz hvplot](https://hvplot.holoviz.org/)
* [pathlib](https://docs.python.org/3/library/pathlib.html)
* [scikit clustering KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
* [scikit decomposition PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
* [scikit preprocessing StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)

---

## Installation Guide

If you have [Anaconda](https://www.anaconda.com/products/distribution) downloaded, then pandas, numpy, SQLAlchemy, and JupyterLab will be part of your package. You can check that they're ready to use by typing the following in your CLI terminal:

```python
conda list jupyterlab
conda list pandas
conda list hvplot
conda list scikit-learn
```

If you need to install hvplot and scikit-learn:

```python
conda install -c pyviz hvplot geoviews
pip install -U scikit-learn
```

then you can check that these were installed by entering:

```python
conda list hvplot
conda list scikit-learn
```

---

## Usage

Open your CLI terminal and type
```python
jupyter lab
```
then JupyterLab will automatically open in your browswer. Use the left side menu bar to search for the `crypto_investments.ipynb` file. Open this file. Then you can use the formaulas in the `.ipynb` file to analyze your `.csv` file(s) and analyze your data.

---

## Contributors

[Rachel Ann Hodson](https://www.linkedin.com/in/rachelannhodson/)
rachelannhodson@gmail.com

---

## License

MIT