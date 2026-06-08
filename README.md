# synent-task2-irisvisualization-krish
# Iris Dataset Visualization

## Problem Statement

Data visualization helps in understanding patterns, relationships, and distributions within a dataset. The objective of this project is to analyze and visualize the Iris dataset using different graphical techniques to identify patterns among various flower species.

---

## Dataset Details

**Dataset Name:** Iris Dataset

**Source:** Kaggle - Iris Species Dataset

**Number of Records:** 150

**Number of Features:** 6

### Features

* Id
* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm
* Species

### Species Present

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## Approach

The following steps were performed:

### 1. Data Loading

* Imported the dataset using Pandas.
* Displayed the first few records for understanding the structure.

### 2. Dataset Exploration

* Examined dataset information.
* Generated summary statistics.
* Checked the distribution of species.

### 3. Data Visualization

#### Bar Chart

* Visualized the count of flowers in each species category.

#### Histogram

* Analyzed the distribution of Sepal Length.

#### Scatter Plot

* Compared Sepal Length and Petal Length.
* Observed relationships among different species.

#### Feature Comparison Chart

* Calculated average values of:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* Compared feature measurements across species.

---

## Results

### Key Findings

#### Species Distribution

* All three species are equally represented in the dataset.

#### Sepal Length Distribution

* Most flowers have sepal lengths between 5 cm and 7 cm.

#### Species Separation

* Iris-setosa is clearly distinguishable from the other two species.
* Iris-versicolor and Iris-virginica show some overlap but can still be differentiated using petal measurements.

#### Feature Comparison

* Iris-virginica has the largest petal dimensions on average.
* Iris-setosa has the smallest petal dimensions.
* Petal measurements are more effective for species classification than sepal measurements.

---

## Outcome

Successfully created multiple visualizations to explore patterns and relationships in the Iris dataset.

Visualizations generated:

* Bar Chart
* Histogram
* Scatter Plot
* Feature Comparison Chart

These visualizations help in understanding species characteristics and can be used as a foundation for future machine learning tasks such as classification.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Author

Krish Kaneria
