# Media-Campaign-Cost-Prediction-for-Convenient-Food-Mart


This repository contains code for devising a machine learning model to predict the cost of media campaigns in Food Mart (CFM) convenience stores based on various features provided in the dataset.

## Dataset Description

The dataset includes the following features:

- **store_sales(in millions)**: Store sales in million dollars.
- **unit_sales(in millions)**: Unit sales in million dollars.
- **Total_children**: Total children in home.
- **avg_cars_at home(approx)**: Average cars at home (approx).
- **Num_children_at_home**: Number of children at home as per customers' filled details.
- **Gross_weight**: Gross weight of item.
- **Recyclable_package**: Indicates whether the food item has a recyclable package.
- **Low_fat**: Indicates whether the food item is low fat.
- **Units_per_case**: Units per case available in each store shelves.
- **Store_sqft**: Store area available in square feet.
- **Coffee_bar**: Availability of a coffee bar in the store.
- **Video_store**: Availability of a video store/gaming store in the store.
- **Salad_bar**: Availability of a salad bar in the store.
- **Prepared_food**: Availability of prepared food in the store.
- **Florist**: Availability of flower shelves in the store.
- **Cost**: Cost on acquiring a customer in dollars.


## Results and Visualization

The repository includes code for data exploration, visualization, model training, and evaluation. Key visualizations include boxplots, histograms, scatterplots, and barplots to understand the distributions and relationships between variables.

The machine learning models used for prediction include:

- **Linear Regression**
- **Lasso Regression**
- **Random Forest Regression**

The performance of each model is evaluated using Root Mean Square Error (RMSE).
