
# Phase 2 Project: Analyzing Movie Trends - What Films Perform Best at the Box Office?

## Overview
This project explores factors that contribute to a movie's box office success. Using data analysis and statistical models, we identify key trends and relationships between production budgets, genres, and audience reception.

## Business Understanding
The company sees major corporations creating original video content and wants to join the industry. However, they lack expertise in movie production. This project explores box office trends to provide actionable insights for launching a successful film studio. Key questions include:

- What genres perform best in terms of worldwide gross revenue?

- How does production budget impact revenue?

- Are factors like runtime, release year, and user ratings significant predictors of box office success?

## Data Understanding and Analysis
The dataset includes movie details such as worldwide gross revenue, production budgets, genres, ratings, and release years. We conducted exploratory data analysis (EDA) to uncover patterns and used statistical methods to validate key insights.  
### Key Columns Used For Analysis:
- Movie - Movie title  
- Start_year - Year of initial screening 
- Runtime_minutes - Duration of the film  
- Genres - Genre of the film  
- Averagerating - Average popularity rating of a film  
- Numvotes - Number of voters of a particular film  
- Release_date - Official date of release to the public  
- Production_budget - Cost of making the movie  
- Domestic_gross - Revenue brought in from the domestic market  
- Worldwide_gross - Revenue brought in from the global market  

## Key Insights
- **Production Budget vs. Revenue:** High-budget movies tend to generate significantly higher revenues.
- **Profitable Genres:** Drama leads in total profit, while genre combinations like Adventure, Animation, and Comedy show strong financial performance.
- **Audience Trends:** Documentaries maintain stable high ratings, while Action and Sci-Fi ratings have gradually declined.

## Key Visuals
📊 *(Add 2-3 key visualizations from your analysis to highlight trends.)*

## Tools Used
- **Programming Language**: Python
- **Libraries:** pandas, seaborn, matplotlib, numpy, scipy, statsmodels, sqlite3

## Business Recommendations
1. **Invest in High-Budget Films**: Larger budgets generally yield higher revenues, but cost-efficiency remains key.
2. **Focus on Profitable Genres**: Prioritize genres and combinations that consistently perform well.
3. **Consider Audience Trends**: Leverage genres with stable audience satisfaction for long-term success.

## Folder Structure
```
📂 Phase-2-Project
 ├── .gitignore
 ├── phase-2-project-Final.ipynb  # Jupyter Notebook with full analysis
 ├── README.md                     # Project Summary
 ├── data/                          # Raw and processed datasets
 └── presentation.pdf/                       # Non-techincal presentation
```

## Conclusion
This analysis provides valuable insights into movie performance trends, helping stakeholders make data-driven decisions in the film industry. Further research could include marketing budgets, streaming data, and audience demographics for a more comprehensive analysis.
