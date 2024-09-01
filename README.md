Name: AYUSHMAN SINGH <br>
Company: CODETECH IT SOLUTIONS<br>
ID: CT6WDS1495<br>
Domain: Data science<br>
Duration: AUGUST 1st, 2024 to SEPTEMBER 15th, 2024<br>

<h1>Output:-</h1><br>

<img src="https://github.com/user-attachments/assets/07752ced-61b5-4fc4-81c4-78e9b1ed7c62">

# Titanic Dataset Analysis

This project provides a basic exploratory data analysis (EDA) of the Titanic dataset. The analysis includes handling missing values, visualizing distributions, and examining relationships between variables. The code is written in Python using popular data science libraries like `pandas`, `matplotlib`, and `seaborn`.

## Dataset

The dataset used in this analysis is publicly available from the Stanford University website:
- [Titanic Dataset](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)

This dataset contains information about passengers on the Titanic, such as their age, fare, and survival status.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static, animated, and interactive visualizations.
- `seaborn`: For making statistical graphics.

## Code Overview

1. **Loading the Dataset**: The dataset is loaded directly from the provided URL using `pandas`.

2. **Initial Data Inspection**:
   - Display the first few rows of the dataset using `head()`.
   - Retrieve basic information about the dataset using `info()`.
   - Generate summary statistics using `describe()`.
   - Check for missing values using `isnull().sum()`.

3. **Handling Missing Data**:
   - Missing values in the `Age` column are filled with the median age.
   - Missing values in the `Embarked` column are filled with the mode (most frequent value).
   - The `Cabin` column, which contains a significant number of missing values, is dropped from the dataset.

4. **Data Visualization**:
   - **Age Distribution**: A histogram is plotted to show the distribution of passenger ages.
   - **Survival Counts**: A bar plot is created to display the counts of survivors and non-survivors.
   - **Age vs. Fare**: A scatter plot is generated to show the relationship between age and fare, colored by survival status.
   - **Correlation Heatmap**: A heatmap is created to visualize the correlation between different numerical features in the dataset.

## Visualization Examples

### Age Distribution
![Age Distribution](path_to_image/age_distribution.png)

### Survival Counts
![Survival Counts](path_to_image/survival_counts.png)

### Age vs. Fare (Colored by Survival)
![Age vs. Fare](path_to_image/age_vs_fare.png)

### Correlation Heatmap
![Correlation Heatmap](path_to_image/correlation_heatmap.png)

## How to Run the Code

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/titanic-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd titanic-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the analysis:
    ```bash
    python analysis.py
    ```

## Conclusion

This project demonstrates how to perform a simple exploratory data analysis using Python. The visualizations provide insights into the distribution of ages, survival rates, and the relationship between different features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




