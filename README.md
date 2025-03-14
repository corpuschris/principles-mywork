# Iris Dataset Analysis

This project explores the **Iris dataset**, a well-known dataset in statistics and machine learning. The dataset consists of **150 samples** of iris flowers, each with four numerical features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

Each flower belongs to one of **three species**: *Setosa, Versicolor, or Virginica*.  
The goal of this project is to analyze, visualize, and interpret the dataset using Python.

---

## Progress So Far

###  **Task 1: Source the Data Set**
- Imported the **Iris dataset** from `sklearn.datasets`.
- Explained what `load_iris()` returns in simple terms.

###  **Task 2: Explore the Data Structure**
- Printed the **shape** of the dataset.
- Displayed the **first and last 5 rows**.
- Listed the **feature names** and **target classes**.

###  **Task 3: Summarize the Data**
- Calculated **mean, min, max, standard deviation, and median** for each feature.

###  **Task 4: Visualize Features**
- Created **histograms** for each feature using `matplotlib`.
- Added **titles and axis labels** to improve readability.

###  **Task 5: Investigate Relationships**
- Created a **scatter plot** comparing **sepal length** and **petal length**.
- Color-coded the points based on the three different species.

###  **Task 6: Analyze Relationship**
- Used **`numpy.polyfit`** to compute a **regression line** for the scatter plot.
- Plotted the **regression line** on top of the scatter plot.

###  **Task 7: Analyze Class Distributions**
- Created **box plots** to show the distribution of **petal lengths** for each species.
- Compared the spread and median values of petal lengths.

###  **Task 8: Compute Correlations**
- Calculated the **correlation coefficients** between all features.
- Displayed the **correlation matrix** as a heatmap using `seaborn` and `matplotlib`.

## How to Run the Code

```bash
# Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn

# Run the script
python iris_analysis.py

## Dependencies & References

- Pandas Documentation (https://pandas.pydata.org/docs/) - Used for data manipulation.
- NumPy Documentation (https://numpy.org/doc/) - Used for numerical operations.
- Matplotlib Documentation (https://matplotlib.org/stable/contents.html) - Used for data visualization.
- Seaborn Documentation (https://seaborn.pydata.org/) - Used for creating statistical plots.
- scikit-learn Documentation (https://scikit-learn.org/stable/) - Used to load the Iris dataset.
