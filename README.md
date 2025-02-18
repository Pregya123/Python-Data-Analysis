# Iris Data Analysis

This project performs comprehensive data analysis and visualization on the Iris dataset using Python, Pandas, NumPy, and Matplotlib.

## Features
- Loads the Iris dataset from an external source.
- Provides exploratory data analysis with descriptive statistics.
- Computes key metrics such as the mean of the `sepal_length` column using NumPy.
- Visualizes the dataset with histograms, scatter plots, and other graphical representations.

## Code Explanation
1. **Loading the Dataset:**
   - The dataset is read from a URL into a Pandas DataFrame using `pd.read_csv()`.
   
2. **Basic Data Analysis:**
   - The first few rows of the dataset are displayed using `data.head()`.
   - Summary statistics such as mean, standard deviation, and percentiles are obtained using `data.describe()`.
   
3. **NumPy Calculations:**
   - The mean of the `sepal_length` column is calculated using `np.mean(data['sepal_length'])`.
   
4. **Data Visualization:**
   - A histogram is plotted to visualize the distribution of `sepal_length` using `plt.hist()`.
   - A scatter plot is created to analyze the relationship between `sepal_length` and `sepal_width` using `plt.scatter()`.
   
## Screenshots
### Sepal Length Distribution
![Sepal Length Histogram](screenshots/sepal_length_hist.png)

### Sepal Length vs Sepal Width
![Scatter Plot](screenshots/sepal_vs_width.png)

## Installation
### Prerequisites
Ensure you have Python installed on your system. Additionally, install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/YourGitHubUsername/iris-data-analysis.git
cd iris-data-analysis
```

2. Run the script:

```bash
python iris_analysis.py
```

## Contributing
Contributions are welcome! If you have suggestions for improvements, please fork the repository and create a pull request.

## License
This project is licensed under the MIT License.

## Author
https://github.com/Pregya123

