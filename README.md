# blinkit-delivery-analysis

## About the Dataset

This project uses a synthetic grocery delivery dataset inspired by quick-commerce platforms like Blinkit. The data includes 10 outlet types across different establishment years (2011-2022), product categories, sales figures, and customer ratings.

Source of the dataset: https://youtu.be/klZj_282ApY?si=_nx0Glys-Pak1bcS

**Note:** This is practice data created for learning purposes, not actual Blinkit operational data.

## Data Cleaning

- Removed Duplicates & unwanted Columns using Power Query
- Identified 10 unique outlet identifiers
- Added +2 for all the Outlet Establishment Year cells to rectify the logical error 


## Data Quality Notes

The dataset contains some logical inconsistencies (e.g., outlet establishment years predating the company's founding). This reinforces that the data is synthetic and created for educational purposes. In a real business scenario, these would be flagged and corrected during data validation.


### Insights from the Orginal Dataset
1. Logical Errors: The Dataset contains the years starting from 2011 but Blinkit was founded in the year 2013. This explains that the data is synthetic and was only created for educational purpose not a real world analysis 

### Customization
1. Created a new sheet 'Locality' and added a table with 2 columns with Outlet Identifier for referencing and 'City' Column for merging.
used VLOOKUP to add the city column in the dataset.

2. Created 'Delivery Days' column to know the frequency of orders by week.


## Recommendations and Conclusions

- OUT019 achieves highest customer rating (4.0) with lowest sales volume (528 orders), indicating a quality-focused niche model.
- Fruits/vegetables, snacks, and household items drive 40% of total sales, Ensure they never stock out.
- Prioritize medium-sized outlets in Tier 2/3 cities where performance per location is strongest.

## Future Scope
The Analysis which is done is basic, There is always room for improvement.
In the Future I may not only customize the blinkit dataset for more insights but also integrate it with other Eternal subsidiaries.

Why did i not perform an analysis on Eternal Ltd. now then?

"Build something imperfect today rather than planning something perfect for tomorrow"


