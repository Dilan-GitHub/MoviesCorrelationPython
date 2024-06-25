# Movies Correlation Project

## About

This project aims to explore the correlation between various factors in the movie industry, such as budget, gross earnings, and other relevant variables. The dataset includes information on movie budgets, gross earnings, and other attributes. The primary objective is to identify significant correlations and provide insights into the factors that influence a movie's financial success.

## Purposes Of The Project

The major aim of this project is to analyze the movie data to understand the relationships between different variables, such as budget and gross earnings, and to identify trends and patterns in the movie industry.

## About Data

The dataset used for this project contains information on various attributes of movies, including:

| Column      | Description                         | Data Type      |
| :---------- | :---------------------------------- | :------------- |
| budget      | The budget of the movie             | INT            |
| gross       | The gross earnings of the movie     | INT            |
| votes       | The number of votes the movie received | INT            |
| released    | The release date of the movie       | DATE           |
| yearcorrect | The year extracted from the release date | VARCHAR(4)     |

### Analysis List

1. Missing Data Analysis
   > Identify and handle any missing data in the dataset to ensure accuracy and consistency.

2. Data Type Correction
   > Correct data types for columns such as budget, gross, and votes to ensure proper analysis.

3. Data Sorting and Duplication Removal
   > Sort the data by gross earnings and remove any duplicate entries.

4. Correlation Analysis
   > Analyze the correlation between budget and gross earnings using scatter plots and regression plots.

## Approach Used

1. **Data Wrangling:**
   - Identify and handle missing data by removing rows with missing values.
   - Correct data types for numerical columns to ensure proper analysis.
   - Extract the year from the release date and store it in a new column named `yearcorrect`.
   - Sort the data by gross earnings and remove any duplicates.

2. **Exploratory Data Analysis (EDA):**
   - Create scatter plots and regression plots to visualize the relationship between budget and gross earnings.
   - Use seaborn and matplotlib for data visualization to identify trends and patterns.

## Conclusion

This project provides insights into the relationship between movie budgets and their gross earnings. By analyzing these correlations, stakeholders in the movie industry can make more informed decisions regarding budget allocation and marketing strategies to maximize a movie's financial success.

For more details, you can view the full Jupyter notebook file [HERE](https://github.com/Dilan-GitHub/PortfolioProjects/blob/main/Movies%20Correlation%20Project.ipynb).



