# House Price Prediction Model

## Project Overview
This project involved building a linear regression model to predict house sale prices based on key features from the King County House Sales dataset. The goal was to create an accessible tool for real estate professionals to get valuable insights into factors influencing house prices so they can make informed decisions to homeowners about selling or renovating their homes.

The model focuses on understanding:
- How different housing features impact sale price.
- Which features have the most significant relationships with price.
- How features interact to affect price.

## Data
The data used is the King County House Sales dataset, containing house sale transactions for King County, USA. It includes useful features about homes like square footage, number of bedrooms and bathrooms, location coordinates, house condition , etc. that serve as predictors in the model.

Data dictionary: `column_names.md`

## Methodology
The project followed a standard machine learning workflow:
1. Data Loading & Cleaning
2. Exploratory Data Analysis
3. Preprocessing & Feature Engineering
4. Model Development & Evaluation
5. Model Optimization

Key libraries used include Pandas, Matplotlib, Seaborn, Scikit-learn, and Statsmodels.

## Key Findings
Some highlights from the analysis include:
- Living area, location, condition, bathrooms were top drivers of price.
- Interactions between features also significantly impacted prices.
- Larger homes with more bathrooms saw a greater boost in prices.
- More bedrooms decreased prices when considered with living area.

The final model scored an R-squared of 0.62, capturing a significant portion of factors influencing prices.

## Future Work
Some areas of improvement:
- Incorporate timeseries data to account for market trends.
- Gather more data like school districts, crime rates, etc.
- Expand on location analysis in the model.

## Repository Contents
- Jupyter Notebook containing full project code and analysis.
- `king_county_house_data.csv` - original dataset.
- `column_names.md` - data dictionary.
- `README.md`

Overall, this project serves as a foundation for an accessible house price prediction application for homeowners and real estate professionals. The techniques can be built upon to enhance model accuracy even further.
