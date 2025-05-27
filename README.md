Iris Dataset Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on the Iris dataset using Python libraries such as pandas, matplotlib, seaborn, and plotly.express. It includes data loading, cleaning, statistical summaries, and various visualizations to uncover patterns and insights.

📁 Dataset

The dataset used is Iris.csv, which contains measurements of iris flowers — specifically sepal and petal lengths and widths — along with their species.

🛠️ Dependencies

Make sure you have the following Python libraries installed:

pip install pandas matplotlib seaborn plotly
📊 Features of the Script

1. Data Inspection
Displays the first five rows.
Shows dataset structure and data types.
Checks for missing values.
Prints summary statistics of numerical features.
2. Data Cleaning
Fills missing numerical values with the median.
Fills missing categorical values with the mode.
Re-checks for missing values after cleaning.
3. Data Aggregation & Analysis
Computes basic statistical descriptions.
Groups data by species to calculate average values for numerical columns.
Calculates and prints the correlation matrix to detect linear relationships.
4. Visualizations
Bar Plot

Displays average petal length for each Iris species.
Scatter Plot

Plots petal length vs. petal width colored by species.
Histograms

Visualizes the frequency distribution of petal length and petal width.
Box & Swarm Plot

Presents a box plot with overlaid swarm plot to show the spread and distribution of petal width.
📌 Notes

Ensure that `Iris.csv` is present in the project directory before running the script. The dataset should be in CSV format with columns for sepal length, sepal width, petal length, petal width, and species.

🚀 Usage

1. Clone this repository or download the files.
2. Make sure all dependencies are installed:
   ```
   pip install pandas matplotlib seaborn plotly
   ```
3. Place `Iris.csv` in the project directory.
4. Run the analysis script (e.g., `python iris_eda.py`).
5. View the generated plots and outputs in your terminal or as image files (if saved).

🙌 Credits

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris) for the Iris dataset.
- Python libraries: pandas, matplotlib, seaborn, plotly.

📄 License

This project is licensed under the MIT License.