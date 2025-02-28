# Indonesian-province-edu-poverty-analysis

## Project Overview

This project analyzes socioeconomic indicators across different provinces, focusing on trends in illiteracy rates, school enrollment rates, and poverty indices from 2019 to 2023. The primary goal is to understand the relationships between these factors and identify patterns or clusters of provinces with similar socioeconomic characteristics.

**This project was developed as an individual assignment for the Data Science course at [Universitas Islam Indonesia] during the [3rd Semester].** It represents the culmination of learned skills and methodologies applied to real-world data analysis.

The analysis uses the following datasets:

*   **Illiteracy Rate Data:** Data on illiteracy rates for various age groups (15+, 15-44, 45+) from 2019 to 2023.
*   **School Enrollment Rate Data:** Data on school enrollment rates for different age groups (12, 13-15, 16-18, 19-24) from 2019 to 2023.
*   **Poverty Index Data:** Poverty Severity Index (P2) data by province from 2019 to 2023.

## Project Structure

The project is structured as follows:

1.  **Data Preprocessing:**
    *   Loading and cleaning the illiteracy rate, school enrollment rate, and poverty index datasets.
    *   Handling missing values.
    *   Merging the datasets into a comprehensive view.
    *  Creation of a new .csv file with the merged data.

2.  **Data Visualization:**
    *   **Trends Over Time:** Visualizing the trends in illiteracy rates, school enrollment rates, and poverty indices across provinces from 2019 to 2023.
    *   **Scatter Plots:** Exploring the relationships between illiteracy rates, school enrollment rates, and poverty indices for the year 2023.
    *   **Distribution of Variables:** Visualizing the distribution of each of the key variables for 2023.
    *   **Correlation Heatmap:** Examining the correlation between illiteracy rate, school enrollment rate, and poverty index for 2023.

3.  **Model Training (K-Means Clustering):**
    *   Selecting relevant features (Illiteracy Rate 2023, Poverty Index 2023).
    *   Standardizing the features.
    *   Using the Elbow Method to determine the optimal number of clusters.
    *   Applying K-means clustering.
    *   Evaluating the clustering using the Silhouette Score.
    *   Interpreting the characteristics of each cluster.

## Key Findings

*   **Trends Over Time:** The time series analysis showed the evolution of each variable in the different provinces.
*   **Relationships:** The scatter plots revealed a correlation between illiteracy rates, school enrollment rates, and the poverty index.
*   **Clustering:** The K-means clustering grouped provinces with similar characteristics.

## Tools and Libraries

*   **Python 3.x**
*   **pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical operations.
*   **matplotlib:** For data visualization.
*   **seaborn:** For enhanced data visualization.
*   **scikit-learn:** For K-means clustering, data scaling, and evaluation metrics.

## Setup and Execution

1.  **Clone the repository:**
```bash
git clone https://github.com/amga-d/Indonesian-province-edu-poverty-analysis.git
```
2. **Install required libraries:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
3.  **Run the Notebook:**
    *  Open the notebook in Google Colab or Jupyter Notebook.
    *  Execute the code cells to reproduce the analysis and visualizations.


## Contact

[Amgad] - [amgad.abdulrazzaq@gmail.com]

[GitHub Profile](https://github.com/amga-d)
