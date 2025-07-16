# Video Games Sales Exploratory Data Analysis (EDA)

## Project Overview

This project performs a comprehensive exploratory data analysis on video game sales data to uncover insights about gaming trends, market preferences, and sales patterns across different regions, genres, platforms, and time periods.

## Dataset

The analysis uses the **Video Game Sales Dataset** (`vgsales.csv`) which contains information about video game sales from various platforms and regions.

### Dataset Features:

- **Rank**: Overall sales rank
- **Name**: Game title
- **Platform**: Gaming platform (e.g., PS2, Xbox, Wii, etc.)
- **Year**: Year of release
- **Genre**: Game genre (Action, Sports, Shooter, etc.)
- **Publisher**: Game publisher
- **NA_Sales**: Sales in North America (in millions)
- **EU_Sales**: Sales in Europe (in millions)
- **JP_Sales**: Sales in Japan (in millions)
- **Other_Sales**: Sales in other regions (in millions)
- **Global_Sales**: Total worldwide sales (in millions)

## Key Analysis Questions

This EDA project answers several important questions about the video game industry:

1. **Most Popular Game Genres** - Which genres dominate the market?
2. **Peak Release Years** - When were the most games released?
3. **Genre Trends by Year** - How have genre preferences changed over time?
4. **Sales Performance by Year** - Which years had the highest global sales?
5. **Genre Release Patterns** - Which genre had the most releases in a single year?
6. **Genre Sales Performance** - Which genre generated the highest sales in a single year?
7. **Platform Analysis** - Which gaming platforms have the highest sales?
8. **Top Individual Games** - Which specific games sold the most copies?
9. **Regional Sales Comparison** - How do sales differ across regions?
10. **Publisher Analysis** - Who are the top publishers by game count and sales?

## Key Findings

### Genre Insights

- **Action** and **Sports** games consistently rank as the most popular genres
- **2009** was a peak year for Action games with **272 releases** and **139.36 million in sales**
- **Shooter** games rank surprisingly high in sales despite fewer releases


### Temporal Trends

- Clear patterns emerge in game release cycles and sales performance
- Certain years show exceptional performance due to major platform launches
- Gaming industry growth trends are visible across the analyzed time period

##  Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## Prerequisites

Before running this analysis, ensure you have the following packages installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

##  Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/raihanromi/Video-Games-Sales-EDA.git
   cd Video-Games-Sales-EDA
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook video_games_sales_eda.ipynb
   ```

3. **Run the analysis**:
   - Execute cells sequentially to reproduce the analysis
   - All visualizations and insights will be generated automatically

## Visualizations Included

The notebook contains various types of visualizations:

- **Count Plots** - Genre and platform distributions
- **Bar Charts** - Sales comparisons and rankings
- **Line Plots** - Temporal trends and growth patterns
- **Heatmaps** - Correlation analysis and regional comparisons
- **Pie Charts** - Regional sales distribution
- **Pair Plots** - Multi-variable relationship analysis

##  Business Insights

This analysis provides valuable insights for:

- **Game Developers** - Understanding market trends and genre preferences
- **Publishers** - Identifying optimal release strategies and target markets
- **Platform Holders** - Recognizing successful platform characteristics
- **Market Analysts** - Tracking industry trends and regional preferences
- **Investors** - Evaluating market opportunities and risks

##  Data Preprocessing

The analysis includes data cleaning steps:

- Filtering games released after 2015 to focus on the main dataset period
- Handling missing values and duplicates
- Data type optimization for analysis

