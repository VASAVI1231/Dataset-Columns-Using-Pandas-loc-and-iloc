# Select Dataset Columns Using Pandas loc and iloc

## Project Overview

This project demonstrates how to select specific rows and columns from a dataset using Pandas.

The main focus of this project is understanding the difference between `loc` and `iloc`.

## Objective

The objective of this project is to learn:

- How to select a single column
- How to select multiple columns
- How to select rows using `loc`
- How to select rows using `iloc`
- How to select specific rows and columns
- How to access individual values from a DataFrame

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Google Colab

## Dataset

The Iris dataset is used for this project.

The dataset contains the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

The dataset is loaded directly using Scikit-learn, so no external dataset download is required.

## loc vs iloc

### loc

`loc` is mainly used for label-based selection.

Example:

```python
df.loc[0:4, ["sepal_length", "species"]]