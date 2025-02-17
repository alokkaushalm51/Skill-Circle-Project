# Zomato Restaurants Exploratory Data Analysis (EDA) Project

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Zomato restaurant data to identify key factors that contribute to the success of restaurants, as measured by their ratings. The project is structured to guide users through various aspects of data analysis, including data cleaning, visualization, and deriving insights from the dataset.

## Key Objectives

1. **Understand the Dataset**: Explore the basic composition of the data, including dimensions, data types, and missing values.
2. **Analyze Restaurant Ratings**: Calculate and visualize the average rating of restaurants and understand the distribution of ratings.
3. **Location-based Analysis**: Identify cities with the highest concentration of restaurants and analyze ratings across different cities.
4. **Cuisine Analysis**: Determine the most popular cuisines and investigate if cuisine variety correlates with ratings.
5. **Price Range Analysis**: Analyze the relationship between price range and restaurant ratings.
6. **Online Order and Table Booking**: Investigate the impact of online order availability and table booking on ratings.
7. **Top Restaurant Chains**: Identify and analyze the top restaurant chains based on the number of outlets and their ratings.
8. **Restaurant Features**: Analyze the impact of features like Wi-Fi, alcohol availability, etc., on ratings.
9. **Sentiment Analysis**: Create a word cloud based on customer reviews to identify common positive and negative sentiments.
10. **Seasonal Trends**: Explore if there are any seasonal trends in restaurant ratings or user reviews.

## Tools and Techniques

- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Plotly, SciPy, Cufflinks.
- **Data Visualization**: Bar charts, scatter plots, word clouds, box plots.
- **Statistical Analysis**: T-tests, summary statistics.

## Dataset

The dataset used in this project is `Zomato_Indian_Restaurants.csv`, which contains information about various restaurants listed on Zomato. The dataset includes details such as restaurant ID, name, establishment type, address, city, locality, latitude, longitude, cuisines, timings, average cost for two, price range, currency, highlights, aggregate rating, rating text, votes, photo count, opentable support, delivery, and takeaway.

## Data Cleaning

1. **Handling Missing Values**: Rows with missing values were removed to ensure data quality.
2. **Removing Duplicates**: Duplicate rows were dropped to avoid redundancy.
3. **Column Removal**: Unnecessary columns such as `zipcode`, `opentable_support`, `photo_count`, `currency`, `url`, `locality`, `votes`, and `country_id` were removed to simplify the dataset.

## Analysis

### Average Rating Calculation

- The average rating for each restaurant was calculated and visualized.
- The top 15 restaurants with the highest average ratings were identified.

### Summary Statistics

- Summary statistics for all numeric columns were provided to understand the distribution and central tendencies of the data.

### Key Insights

- **General Summary**: The dataset contains 211,944 entries with 26 columns. There are significant missing values in columns like `zipcode`, `cuisines`, `timings`, and `opentable_support`.
- **Data Distribution**: High standard deviation in certain columns suggests significant variability in the dataset.
- **Identifiers & Location Data**: The dataset covers multiple city locations with unique restaurant entries.
- **Pricing & Rating Insights**: The average cost for two ranges from 0 to 30,000, with a median cost of 400. The majority of restaurants have ratings above 3.0.
- **User Engagement & Media Presence**: Some restaurants have up to 17,702 photos, indicating high-traffic restaurants.
- **Delivery & Takeaway Services**: Values are -1 and 1, indicating possible binary encoding (1 for available, -1 for not available).

## Usage

To run the analysis, ensure you have the necessary Python libraries installed. You can install them using pip:

```bash
pip install pandas numpy seaborn matplotlib plotly scipy cufflinks
```

Load the dataset and follow the steps outlined in the Jupyter notebook to perform the EDA.

## Conclusion

This project provides a comprehensive analysis of Zomato restaurant data, offering insights into various factors that influence restaurant ratings. The findings can help stakeholders make informed decisions to improve restaurant performance and customer satisfaction.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Zomato for providing the dataset.
- Python community for the extensive libraries and tools used in this project.

## Contact


