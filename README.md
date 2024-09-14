# Gender Disparity in Education: Data Analysis Project

This project investigates gender disparity in youth literacy rates, particularly focusing on its relationship with other factors like gross primary education enrollment and unemployment rates. The analysis is conducted using Python with various data science libraries.

## Project Structure

1. **Loading the Dataset**: 
    - The dataset used in this analysis is related to global education statistics, focusing on literacy rates and education enrollment.
    
2. **Data Exploration and Cleaning**: 
    - In this step, we explore the structure of the dataset, check for missing values, and clean the data by handling anomalies to prepare it for analysis.
    
3. **Calculating Gender Disparity**: 
    - We calculate gender disparity in youth literacy rates (aged 15-24) to understand the gap between males and females in education.
    
4. **Exploratory Data Analysis (EDA)**: 
    - We analyze the relationship between gender disparity, gross primary education enrollment, and the unemployment rate. Visualizations and summary statistics are used to explore these variables.

5. **Visualization**:
    - Visualizations are created to display the relationship between gender disparity in youth literacy and other variables such as primary education enrollment.
    
6. **Modeling and Analysis**:
    - Statistical models such as linear regression are applied to understand the impact of these variables on gender disparity.
  
## Dependencies

To run this project, the following Python libraries are required:

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
```

You can install them using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Running the Project

1. **Clone the repository**:
    ```bash
    git clone <repo_url>
    ```

2. **Navigate to the project directory**:
    ```bash
    cd project_directory
    ```

3. **Run the Jupyter notebook**:
    - Open the `final_project.ipynb` file in Jupyter and run each cell sequentially.
    - Make sure the dataset file (`Global_Education.csv`) is in the same directory.

## Dataset

The dataset used in this project contains global education statistics. It includes columns such as:

- `Youth_15_24_Literacy_Rate_Male`
- `Youth_15_24_Literacy_Rate_Female`
- `Gross_Primary_Education_Enrollment`
- `Unemployment_Rate`
- And others

## Results

The project provides insights into gender disparity in education across different countries, and the relationship between gender disparity and other factors such as education enrollment and unemployment.

## License

This project is licensed under the MIT License.

---
