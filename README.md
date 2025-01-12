# Automobile Dataset Analysis

## Overview

This project involves analyzing an automobile dataset to uncover insights about various features and their impact on car prices. Using Python and libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn, we perform data cleaning, visualization, and predictive modeling.

## Dataset

The dataset used in this project is the [Automobile Dataset](https://archive.ics.uci.edu/ml/datasets/Automobile) from the UCI Machine Learning Repository. The dataset contains various attributes of automobiles, including:

- `make`: Manufacturer of the car
- `model`: Model of the car
- `year`: Year of manufacture
- `mileage`: Total mileage of the car
- `horsepower`: Engine power
- `curb-weight`: Weight of the car
- `engine-size`: Size of the engine
- `normalized-losses`: Normalized losses in terms of price
- `price`: Price of the automobile (target variable)

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started

### Prerequisites

Make sure you have Python and the required libraries installed. You can set up a virtual environment and install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Cloning the Repository

You can clone this repository to your local machine using the following command:

```bash
git clone  https://github.com/Laliforu/Data-Analysis-Project
```

### Running the Project

1. Navigate to the project directory:

   ```bash
   cd automobile-dataset-analysis
   ```

2. Open a Jupyter Notebook and run the analysis:

   ```bash
   jupyter notebook
   ```

3. Open `automobile_analysis.ipynb` and execute the cells to perform data analysis and visualization.

## Data Analysis Steps

1. **Data Loading**: Load the dataset using Pandas.
2. **Data Cleaning**:
   - Handle missing values.
   - Convert data types where necessary.
3. **Data Visualization**:
   - Generate descriptive statistics.
   - Create visualizations such as histograms, scatter plots, and correlation heatmaps.
4. **Predictive Modeling**:
   - Split the dataset into training and testing sets.
   - Train a linear regression model to predict car prices.
   - Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R-squared (R²).

## Results

The analysis reveals various insights regarding the impact of features on car prices. The predictive model demonstrates its ability to estimate prices based on the selected features, providing valuable insights for potential buyers and manufacturers.

## Contributing

Contributions to this project are welcome! If you have suggestions or improvements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- UCI Machine Learning Repository for providing the automobile dataset.
- The open-source community for the valuable libraries used in this project.
