# Housing Rental Analysis for San Francisco
![Moh Jaiswal](Images/6-4-challenge-image.png)
## Moh Jaiswal

## Introduction

This project aims to analyze the housing rental market data for San Francisco and identify potential investment opportunities. By leveraging data visualization techniques such as aggregation, interactive visualizations, and geospatial analysis, we will gain insights into the San Francisco real estate market.

## Analysis Deliverables

To accomplish our objectives, we will create a Jupyter notebook with the following deliverables:

1. Calculation and visualization of housing units per year.
2. Calculation and visualization of average prices per square foot.
3. Comparison of average prices by neighborhood.
4. Development of an interactive neighborhood map.
5. Creation of a compelling data story.

## Data Files

We will utilize the following data files for our analysis:

- `housing_per_year.csv`: Contains data on housing units per year.
- `neighborhoods_coordinates.csv`: Provides the coordinates of neighborhoods.
- `sfo_neighborhoods_census_data.csv`: Includes census data for San Francisco neighborhoods.

## Analysis Steps

### Housing Units per Year

1. Group the data by year and calculate the mean for each group.
2. Create a bar chart using `hvplot` to visualize the housing units per year.

### Average Sale Prices per Square Foot

1. Group the data by year and calculate the average prices.
2. Determine the lowest gross rent reported within the included years.
3. Filter out the "housing_units" column and create a new DataFrame named `prices_square_foot_by_year`.
4. Use `hvplot` to create a line plot for the `prices_square_foot_by_year` DataFrame.
5. Analyze the data to identify any drops in average sale price per square foot compared to the previous year and the corresponding change in gross rent.

### Average Sale Prices by Neighborhood

1. Group the data by year and neighborhood, calculating the mean for each group.
2. Filter out the "housing_units" column to focus on average sale price per square foot and gross rent.
3. Create an interactive line plot using `hvplot` to compare sale prices per square foot and gross rent over the years, with the x-axis representing the year and the interactive widget showing different neighborhoods.
4. Analyze the plot to gain insights into the average sale price per square foot for specific neighborhoods in different years.

### Interactive Neighborhood Map

1. Read the `neighborhood_coordinates.csv` file and create a DataFrame named `neighborhood_locations_df`, setting "Neighborhood" as the index column.
2. Group the original DataFrame by neighborhood, calculating the mean for each group.
3. Merge the `neighborhood_locations_df` DataFrame with the grouped DataFrame to add coordinates to each neighborhood.
4. Use the `folium` library to create an interactive map with markers for each neighborhood.
5. Analyze the map to identify neighborhoods with potential investment opportunities.

## Conclusion

In conclusion, this analysis provides valuable insights into the housing rental market in San Francisco. The growth rate for rental income shows a significant upward trend, indicating high potential for generating income from rental properties. On the other hand, the price per square foot remains relatively flat in comparison, although this may appear flatter due to both metrics sharing the same axis.

While it is true that rental income growth outpaces the increase in square footage price (430% vs. 122%), it's important to note that both metrics experience a high percentage change. A more detailed comparison can be seen in the optional diagram in line 15. It's worth mentioning that gross rent includes all livable areas, not just one square foot.

The decision to buy or rent a property depends on the individual's goals, budget, tenure, and ability to carry out the decision. For those purely seeking to create value, focusing on buying a house is recommended, as the analysis shows that gross rent outpaces housing prices over time. By owning their own home, individuals not only avoid paying more in rent but also have the potential to earn income from real estate.

For individuals looking to earn income from real estate, owning a home in a high-rent neighborhood while living in a location with moderate rents is a viable strategy. This approach allows for capturing the higher rental income from the investment property while benefiting from lower living expenses.

We invite other collaborators to take this project forward and further improve upon the analysis. By combining diverse perspectives and expertise, we can enhance the accuracy and applicability of the findings, leading to better-informed decisions in the real estate market.

## Legal Disclaimer: 

### This analysis is for educational and research purposes only. It is not intended to provide financial or investment advice. Please be cautious and conduct thorough research before making any investment decisions. The owner of this repository is not liable for any actions taken based on the information provided. The findings and conclusions in this repository should not be considered as a substitute for professional advice.
---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
