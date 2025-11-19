# Iris Dataset Analysis

## Description

This Jupyter Notebook demonstrates how to **load, explore, analyze, and visualize** the classic Iris dataset using Python libraries **Pandas**, **Matplotlib**, and **Seaborn**.

The notebook covers:

* Loading the Iris dataset into a Pandas DataFrame
* Exploring the data structure and checking for missing values
* Computing basic statistics (mean, median, standard deviation)
* Grouping data by species to analyze differences
* Creating four types of visualizations:

  * Line chart
  * Bar chart
  * Histogram
  * Scatter plot
* Observations and insights based on the analysis

## Dataset

* **Source:** Iris dataset from `sklearn.datasets.load_iris()`
* **Features:**

  * `sepal length (cm)`
  * `sepal width (cm)`
  * `petal length (cm)`
  * `petal width (cm)`
* **Target:**

  * `species` (`setosa`, `versicolor`, `virginica`)

## Libraries Used

* `pandas` — data manipulation and analysis
* `matplotlib` — plotting charts and graphs
* `seaborn` — enhanced statistical visualizations
* `sklearn.datasets` — loading the Iris dataset

## How to Run

1. Make sure Python 3.x is installed.
2. Install required libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

3. Open the notebook in **Jupyter Notebook** or **VS Code**.
4. Run each cell sequentially to see the data analysis and visualizations.

## Observations

* Iris-setosa has smaller petals compared to other species.
* Iris-virginica generally has the largest sepal and petal measurements.
* Positive correlation exists between sepal length and petal length.
* Some feature overlaps exist, indicating multiple features are needed for accurate classification.

## Author

Ian Njeru
