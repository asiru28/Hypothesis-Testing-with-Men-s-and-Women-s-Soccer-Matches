# Hypothesis-Testing-with-Men-s-and-Women-s-Soccer-Matches

# Overview/Introduction

As a sports journalist specializing in soccer analysis, you’ve observed that more goals might be scored in women's international soccer matches compared to men's. To validate this observation, you decide to perform a statistical hypothesis test using data from official FIFA World Cup matches since January 1, 2002. This analysis aims to determine whether there is a statistically significant difference in the number of goals scored between men's and women's matches.

# Objectives

1. Compare the mean number of goals scored in men's and women's FIFA World Cup matches since 2002.
2. Perform a hypothesis test to determine if women's matches have significantly more goals than men's matches.
3. Provide insights to support or refute the initial observation for an investigative article.

# Data Source

The analysis uses two datasets:
  1. women_results.csv: Contains results of women's international soccer matches.
  2. men_results.csv: Contains results of men's international soccer matches.

Both datasets include the following columns:
  - date: Date of the match.
  - home_team: Name of the home team.
  - away_team: Name of the away team.
  - home_score: Goals scored by the home team.
  - away_score: Goals scored by the away team.
  - tournament: Type of tournament (e.g., FIFA World Cup).

# Tools Used

- Python Libraries: Pandas, Matplotlib, Pingouin
- Statistical Test: Mann-Whitney U test (Wilcoxon-Mann-Whitney test) for comparing two independent samples.
- Data Visualization: Histograms for exploring the distribution of goals scored.

# Insights

1. Data Filtering:
    - The datasets were filtered to include only FIFA World Cup matches played since January 1, 2002.
2. Goal Distribution:
    - Histograms were used to visualize the distribution of goals scored in men's and women's matches.
3. Hypothesis Testing:
    - A right-tailed Mann-Whitney U test was performed to compare the number of goals scored in women's and men's matches.

# Key Findings

1. Hypothesis Test Result:
    - The p-value (0.0051) is less than the significance level (0.01), leading to the rejection of the null hypothesis.
    - This indicates that women's international soccer matches have significantly more goals than men's matches.
2. Goal Comparison:
    - Women's matches tend to have a higher average number of goals compared to men's matches in the analyzed dataset.

# Recommendations

1. Article Focus:
    - Use the findings to write an investigative article highlighting the higher goal-scoring nature of women's international soccer matches.
2. Further Analysis:
    - Explore other tournaments (e.g., continental championships) to see if the trend holds across different competitions.
3. Audience Engagement:
    - Leverage the insights to engage subscribers with data-driven content about the evolving dynamics of international soccer.

# How to Use This Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, matplotlib, pingouin).
3. Run the Jupyter Notebook (Hypothesis Testing with Men's and Women's Soccer Matches.ipynb) to reproduce the analysis.
4. Explore the datasets and modify the code to conduct further analysis or test additional hypotheses.
