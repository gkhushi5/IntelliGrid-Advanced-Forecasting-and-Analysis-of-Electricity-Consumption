
- **data/**: Contains raw, processed, and external datasets.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and model development.
- **scripts/**: Python scripts for data preprocessing, feature engineering, and model implementation.
- **models/**: Saved models and relevant files.
- **results/**: Outputs of the analysis, including visualizations and reports.

## Getting Started

### Prerequisites

To run this project, you'll need the following software and libraries:

- Python 3.8+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- TensorFlow
- Matplotlib
- Seaborn

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/gkhushi5/IntelliGrid.git
    cd IntelliGrid
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. **Data Preprocessing**: Run the preprocessing scripts to clean the data and combine date and time columns.

    ```bash
    python scripts/preprocess_data.py
    ```

2. **Exploratory Data Analysis (EDA)**: Use the notebooks in the `notebooks/` directory to conduct EDA and visualize feature relationships.

3. **Model Implementation and Evaluation**: Implement and evaluate time series forecasting models using the provided notebooks and scripts.

4. **Feature Engineering**: Investigate the impact of various features and create new ones using the feature engineering scripts.

5. **Model Tuning and Validation**: Tune hyperparameters and validate models to ensure optimal performance.

6. **Future Consumption Prediction**: Generate forecasts for future electricity consumption and interpret the results.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to improve the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

I acknowledge the contributions of all the libraries and tools used in this project.
