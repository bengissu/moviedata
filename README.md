## Movie Data Analysis for the Next Movie Selection in a Budget

**Repository:** [bengissu/moviedata](https://github.com/bengissu/moviedata)  
**Owner:** bengissu

---

## Overview

This project is an analysis of movie data aimed at guiding **Sussex Productions** in selecting their next movie within a constrained budget. The company is recovering from a previous project, a comedy-action-thriller with a budget of £500K, which only grossed £100K. With the prospect of securing a £1.5 million investment, this analysis provides insights into making a more profitable movie selection.

---

## Dataset

The analysis uses **IMDB movie metadata** provided in `movie_metadata.csv`. The data file includes information such as genres, budget, gross earnings, language, country, and more. For analysis purposes, all budgets have been converted to GBP.

---

## Project Files

- **README.md**: Overview and instructions for the project.
- **Report1bengisu.ipynb**: Jupyter Notebook containing the detailed analysis, data wrangling, visualizations, and recommendations.
- **movie_metadata.csv**: The movie dataset used for analysis.

---

## Project Instructions

As a data scientist at **SussexBudgetProductions**, you are tasked with analyzing the provided IMDB data and formulating an actionable plan to maximize the profitability of the next movie production. The project focuses on three main areas:

1. **Exploratory Data Analysis (EDA)**:
   - Cleaned and wrangled the dataset by dropping NaN values.
   - Split the data into training and testing sets for robust analysis.
   - Created a new **profit column** to analyze profitability in relation to various features.
   - Investigated numerical features using **Pearson's correlation coefficient**.
   - Analyzed categorical features by grouping data and examining **mean profits** across categories.

2. **Hypothesis Testing**:
   - Developed hypotheses to identify key features of the most profitable movies.
   - Conducted tests to assess the relationship between movie attributes (e.g., genre, country, language) and profitability.
   - Some hypotheses, such as "Comedy Drama Music" being profitable, couldn't be statistically validated due to limited data.

3. **Actionable Recommendations**:
   - Identified that **genres**, **language**, **country**, and **color** are significant predictors of profit.
   - Found that **actors**, **Facebook likes**, or **IMDB scores** have a lesser impact on profitability.
   - Recommended focusing on **Comedy Drama and Music** genres due to their profitability potential.
   - Suggested prioritizing movies produced in the **USA** and **English-language** films, as they tend to be more profitable.

---

## Summary of Findings

- **Data Wrangling**: Dropped NaN values, split data for training/testing, and calculated profit.
- **Profit Drivers**:
  - Genres, language, and country were key factors influencing profitability.
  - Films produced in **English** and **USA** showed a higher profitability margin.
- **Challenges**: Limited data for certain profitable genres like "Comedy Drama Music" meant that statistical significance could not always be achieved.
- **Key Insight**: While the **USA/English-language** films were more profitable overall, individual genre selection is critical to align with budget constraints and profitability goals.

---

## Recommendations for Next Steps

1. **Targeted Genre Selection**: Focus on producing **Comedy Drama Music** movies as a potentially profitable niche within the £1.5 million budget.
2. **Focus on USA Market**: Consider making movies primarily for the **USA** market and in **English**, as these factors were associated with higher profits.
3. **Data-Driven Approach**: Continue refining hypotheses and gather more data to increase statistical power, especially for niche genres.

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/bengissu/moviedata.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd moviedata
   ```
3. Open the Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook Report1bengisu.ipynb
   ```
4. Review the data in `movie_metadata.csv` for an overview of movie attributes and profitability metrics.

---

## Tools and Techniques Used

- **Python**: Data manipulation and analysis.
- **Pandas**: For data wrangling and cleaning.
- **Matplotlib/Seaborn**: For data visualization.
- **Scipy**: For hypothesis testing.
- **Jupyter Notebook**: Interactive data exploration and reporting.

---

## Acknowledgements

This project is part of the **Data Science Research Method Module** at **Sussex University**. The analysis and recommendations are based on publicly available IMDB data, converted to GBP for uniformity.

---

## Contact

For questions or feedback, please reach out to [bengissu](https://github.com/bengissu).

