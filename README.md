# Housing Rental Analysis for San Francisco

![Header Housing San Fran](headerhousingsanfran.png)
### By Moh Jaiswal

## Introduction

This project explores the San Francisco housing rental market to unearth potential investment opportunities. Utilizing data visualization tools, including aggregation, interactive visualizations, and geospatial analysis, we delve into the intricacies of the San Francisco real estate market.

## Analysis Deliverables

Our Jupyter notebook comprises several key deliverables:

1. Visualization of housing units per year.
2. Analysis of average prices per square foot.
3. Comparative study of average prices across neighborhoods.
4. Interactive neighborhood mapping.
5. Crafting a compelling narrative from data.

## Data Files

The following datasets underpin our analysis:

- `housing_per_year.csv`: Housing units data annually.
- `neighborhoods_coordinates.csv`: Neighborhoods' geospatial coordinates.
- `sfo_neighborhoods_census_data.csv`: Census data of San Francisco neighborhoods.

## Analysis Steps

### Housing Units per Year

- Grouping and mean calculation of yearly data.
- `hvplot` bar chart to showcase housing units annually.

### Average Sale Prices per Square Foot

- Yearly grouping and average price calculation.
- Identification of the lowest reported gross rent.
- Creation of `prices_square_foot_by_year` DataFrame.
- Line plot visualization using `hvplot`.
- Analysis of year-over-year average sale price changes.

### Average Sale Prices by Neighborhood

- Grouping data by year and neighborhood.
- Focusing on average sale price per square foot and gross rent.
- Interactive line plot comparison using `hvplot`.
- Neighborhood-specific price trend analysis.

### Interactive Neighborhood Map

- Creation of `neighborhood_locations_df` from `neighborhood_coordinates.csv`.
- Grouping and mean calculation by neighborhood.
- Merging data with coordinates for mapping.
- Interactive mapping with `folium`.
- Identification of neighborhoods with investment potential.

## Conclusion

Our analysis offers insights into the San Francisco housing rental market. Notably, rental income growth outpaces square footage price increases, indicating lucrative rental property investment opportunities. The decision between buying or renting hinges on personal goals and financial capacity. A strategy of owning in high-rent areas while residing in moderate-rent neighborhoods can optimize investment returns. We welcome further contributions to enhance this analysis.

## Badges

[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)](https://github.com/mohjaiswal/HousingRentalAnalysis-SanFrancisco)

## Legal Disclaimer

### This analysis is for educational and research purposes only and should not be construed as financial or investment advice. Exercise caution and conduct thorough research before any investment decisions. The repository owner disclaims liability for actions based on this information. The content is educational, not professional advice.

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
