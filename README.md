# Myntra WeForShe ML Project

This project is an interactive Streamlit dashboard for analyzing e-commerce data from Myntra. The dashboard provides several functionalities including:

1. Popularity score calculation for products.
2. Trend extraction from customer reviews.
3. Real-time sales forecasting using ARIMA.
4. Interactive data visualization.

## Features

- **Popularity Score**: Calculate and display the popularity score for each product.
- **Sales Forecasting**: Forecast future sales using ARIMA model.
- **Trend Predictions**: Extract and display trends from customer reviews.
- **Interactive Dashboard**: View various analytics and insights through an interactive interface.

## Dataset

The dataset used in this project is a synthetic e-commerce dataset with the following columns:

- `id`: Unique ID
- `name`: Product name
- `img`: ";" separated images
- `asin`: None
- `price`: Selling price
- `mrp`: Original price
- `rating`: Average of total rating
- `ratingTotal`: Verified consumers
- `discount`: If the digit is in hundreds, then it is price discount else %
- `seller`: Brand name
- `purl`: Product URL on Myntra
- `sales`: Synthetic sales data
- `reviews`: Synthetic reviews data
- `popularity_score`: Calculated popularity score
- `trends`: Extracted trends from reviews

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```sh
    git clone https://github.com/nazma27/Myntra_WeForShe_Project
    cd myntra
    ```

2. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
-> for User interface:
    ```sh
    streamlit run 03_user_app.py 
    ```

-> for Client interface:
   ```sh
    streamlit run 04_project.py.py 
   ```

## Usage

1. **Popularity Score Prediction**:
    - Enter a product ID or name in the input box to get its popularity score.

2. **Dashboard**:
    - View the dataset and various visualizations on the main dashboard page.

3. **Sales Forecast**:
    - The sales forecast graph shows historical sales and predicted future sales.

4. **Trend Predictions**:
    - The trends extracted from customer reviews are displayed.
## Requirements

- Python 3.7+
- Pandas
- Numpy
- Scikit-learn
- Statsmodels
- Matplotlib
- Streamlit

