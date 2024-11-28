# California Housing Prices Analysis
This project explores the California Housing dataset to visualize and analyze key features related to housing prices. Using Python, the analysis focuses on creating various scatter plots and histograms to identify trends and relationships between housing prices and other factors such as location, population, and income levels.

## Dataset 
The dataset used for this project, _housing.csv_, is from the StatLib repository. It includes features such as:
- Longitude
- Latitude (geographic location)
- Housing_median_age
- Total_rooms
- Total_bedrooms
- Population
- Households
- Median_income
- Median_house_value
- Ocean_proximity

## Methodology 
1. Data Loading and Exploration
   - Imported the dataset into a Pandas DataFrame.

2. Data Cleaning
   - Identified and handled missing values:
       - Located rows with missing data using ```.isnull()``` and inspected them.
       - Dropped rows or columns with significant missing data (```dropna()``` and ```drop()``` functions).

3. Data Analysis
   - Explored the relationship between geographic features and housing prices using scatter plots.
   - Investigated the correlation between features such as median income, population, and median house value.
   - Analyzed the impact of proximity to the ocean on housing prices.
   - Evaluated household density and its relationship with median income and median house value.

4. Visualization
   - Used Matplotlib to visualize the data
   - Histograms: Created a histogram to visualize the distribution of features such as housing prices, income, and population.
   - Scatter Plots: Developed various scatter plots to understand spatial and feature-based relationships:
       - Basic Scatter Plot: Plotted housing locations using longitude and latitude.
       - Enhanced Scatter Plot: Used color and size encoding to represent housing prices, population, and income visually.
       - Households Scatter Plot: Analyzed the relationship between household density and median income.

## Code Usage
1. Install Python Libraries:
   - You only need Python installed with the pandas library. Install it with: --> ```pip install pandas```

2. Run the Script:
   - Use the following command in your terminal to execute the analysis: --> ```python california_housing_analysis.py```

3. View the Output:
   - The script will display histograms for feature distributions and scatter plots displaying geographic trends, population density, and the relationship between median income and housing prices.

## Results 
- A histogram showing feature distributions.
- Scatter plots:
   - Housing locations.
   - Geographic representation of median house values and population density.
   - Household density vs. median income.

## Technologies Used
- **Python**: The primary language used for analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Jupyter Notebook**: For an interactive environment to run and display code.
