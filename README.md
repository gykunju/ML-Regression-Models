# REGRESSION MODELS
The project contains three different Analysis and prediction models
 - California Housing
 - Blueberry Project
 - Real Estate

### California Housing Price Prediction
## Overview
This project involves building and evaluating a linear regression model to predict housing prices in California based on various features such as median income, housing median age, total rooms, and more. The goal is to understand the relationship between these features and housing prices and to create a model that can accurately predict the price of a house given its features.

## Project Structure
The project is organized into the following sections:

## Data Importation and Exploration

The California Housing dataset is loaded using pandas and initial exploratory data analysis (EDA) is conducted to understand the structure and distribution of the data.

Various features are visualized to identify potential correlations and trends.

## Data Preprocessing
The data is preprocessed to handle missing values, encode categorical variables (if any), and scale the features.

The dataset is split into training and testing sets to ensure that the model is evaluated on unseen data.

## Model Building
A linear regression model is implemented using the scikit-learn library.

The model is trained on the training set, and its coefficients are analyzed to understand the impact of each feature on the housing price.

## Model Evaluation
The performance of the model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

Residual plots and other visualizations are used to assess the model's fit and to check for any patterns in the residuals that might indicate issues like heteroscedasticity.

## Model Interpretation
The coefficients of the linear regression model are interpreted to understand the relationship between the features and the target variable (housing price).

Insights are drawn from the model about which features are most influential in predicting housing prices.

## Conclusion and Recommendations

The findings from the model evaluation are summarized, and recommendations are provided on how the model can be used in a real-world setting.

Suggestions for improving the model or extending the analysis are discussed.

## Key Findings
### Feature Importance:
The analysis reveals the key features that most strongly predict housing prices, such as median income and house age.

## Model Performance:

The linear regression model provides a baseline performance for predicting housing prices. The evaluation metrics give an indication of how well the model generalizes to new data.

## Tools and Libraries
The following Python libraries are used in this project:

- pandas: For data manipulation and analysis.
- scikit-learn: For implementing the linear regression model and evaluation metrics.
- Matplotlib and Seaborn: For data visualization.
- NumPy: For numerical operations.


### Real Estate Dataset
## Overview
This dataset contains information about various real estate properties located in Pune, Maharashtra, India. The dataset includes details about the properties, such as their type, area, price, and the amenities available in the respective townships or societies.

## Dataset Summary
Number of Entries: 200
Number of Columns: 17

## Columns Description:
- Sr. No.: A unique identifier for each property.
- Location: The city and state where the property is located (e.g., Pune, Maharashtra, India).
- Sub-Area: The specific locality or sub-area within the city (e.g., Bavdhan, Kharadi).
- Property Type: The type of property (e.g., 1 BHK, 2 BHK, 3 BHK).
- Property Area in Sq. Ft.: The area of the property in square feet.
- Price in lakhs: The price of the property in lakhs of Indian Rupees.
- Price in Millions: The price of the property in millions of Indian Rupees.
- Company Name: The name of the real estate company or developer.
- TownShip Name/ Society Name: The name of the township or society where the property is located.
- Total TownShip Area in Acres: The total area of the township in acres.
- ClubHouse: Indicates whether the township or society has a clubhouse (Yes/No).
- School / University in Township: Indicates the presence of a school or university within the township (Yes/No).
- Hospital in TownShip: Indicates the presence of a hospital within the township (Yes/No).
- Mall in TownShip: Indicates the presence of a mall within the township (Yes/No).
- Park / Jogging track: Indicates the presence of a park or jogging track within the township (Yes/No).
- Swimming Pool: Indicates the presence of a swimming pool within the township (Yes/No).
- Gym: Indicates the presence of a gym within the township (Yes/No).

## Data Characteristics
The dataset includes a mix of categorical and numerical data.

The Price in lakhs and Price in Millions columns are numerical values representing the price of the property in different units.

Amenities such as ClubHouse, School / University in Township, Hospital in TownShip, Mall in TownShip, Park / Jogging track, Swimming Pool, and Gym are represented as categorical variables (Yes/No).

## Notes
Some columns have missing values, particularly in the Total TownShip Area in Acres and Price in Millions columns.

The dataset contains both lower and uppercase representations of certain categorical values, which should be standardized for consistent analysis.

Usage
This dataset can be used for various real estate analysis tasks, such as:

Analyzing property prices based on different factors like location, property type, and amenities.

Comparing the availability of amenities across different townships.

Predictive modeling for real estate pricing based on the provided features.

## Example Analysis
- Property Types: The dataset includes a variety of property types ranging from 1 BHK to 6BHK, as well as commercial properties like shops.
- Locations: Properties are spread across various localities in Pune, including Baner, Bavdhan, Kharadi, etc.
- Amenities: Most properties have access to essential amenities like parks, gyms, and swimming pools, with varying availability of schools, hospitals, and malls within the townships.
