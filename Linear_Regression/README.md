# Linear Regression Implementation and Sklearn Comparison

This repository contains the implementation of various linear regression algorithms from scratch, as well as a comparison with the results obtained using `sklearn`. 
The project explores and evaluates different regression tricks including:

- Simple Trick
- Absolute Trick
- Square Trick
- Sklearn's Linear Regression Model

---

## Dataset

The dataset used for this project is the **[Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)**, which includes information about housing prices and features such as area, number of rooms, and other attributes.

---

## Project Structure

- `data/`: Contains the housing dataset.
- `notebooks/`: Jupyter notebooks with implementation and analysis.
- `src/`: Python scripts for various algorithms.
- `README.md`: Overview of the project.
- `results/`: Outputs, such as plots and performance metrics.

---

## Implementation Details

1. **Regression Tricks**:
   - **Simple Trick**: Updates model parameters using a basic update rule.
   - **Absolute Trick**: Adjusts parameters based on absolute error.
   - **Square Trick**: Minimizes squared error, achieving almost perfect fits.

2. **Model Evaluation**:
   - **Metrics**: Mean Squared Error (MSE) and Mean Absolute Error (MAE) for training and testing data.
   - **Comparison**: Results from manually implemented algorithms versus sklearn's `LinearRegression`.

---

## Results

### Performance Metrics

| Model                | Train MSE       | Train MAE       | Test MSE        | Test MAE       |
|----------------------|-----------------|-----------------|-----------------|----------------|
| Simple Trick         | 3.31e12         | 1.41e6          | 4.23e12         | 1.52e6         |
| Absolute Trick       | 3.31e12         | 1.41e6          | 4.23e12         | 1.52e6         |
| Square Trick         | 2.88e-17        | 3.93e-9         | 4.18e-17        | 4.84e-9        |
| Sklearn Model        | 1.14e-18        | 7.54e-10        | 1.39e-18        | 8.42e-10       |

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/afafrafat77/Machin_Learning_Models/Linear-Regression.git
   cd Linear-Regression
