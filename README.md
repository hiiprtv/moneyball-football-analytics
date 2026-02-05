# Moneyball Football Analytics

## Project Overview:

Moneyball Football Analytics is a data-driven scouting tool designed to identify undervalued football players across Europe’s Top 5 leagues using performance-to-salary ratios and machine learning techniques.
The goal is to replicate a Moneyball-style approach to football recruitment—finding high-impact players who deliver strong on-field performance relative to their market value.

This project is aimed at supporting clubs, analysts, and scouts in making objective, data-backed transfer decisions.

 ## Objectives:

- Identify undervalued players based on performance vs salary/market value

- Build a player efficiency score using advanced metrics

- Apply machine learning to cluster and rank players

- Provide insights for budget-efficient recruitment strategies

 ## Data Sources:

- Player performance statistics (goals, assists, xG, xA, defensive actions, minutes played, etc.)

- Player salary / market value data

## League coverage:

- Premier League

- La Liga

- Serie A

- Bundesliga

- Ligue 1

(Data collected from publicly available football statistics sources)

## Methodology:

- Data Cleaning & Preprocessing

- Handling missing values

- Normalizing performance metrics

- Filtering by minutes played

- Feature Engineering

- Performance-to-salary ratio

- Per-90 metrics

- Composite performance scores

- Machine Learning

- Clustering players using algorithms like K-Means

- Identifying player archetypes and hidden value segments

- Ranking System

- Scoring players based on efficiency

- Highlighting top undervalued candidates by position and league

 ## The "Scout Score" Formula
- To identify true value, the project employs a composite index:
  
- $$Scout\ Score = \text{Performance\ Raw} \times \left(\frac{25}{Age}\right) \times \text{Fame\ Factor}$$
  
- Note: The "Fame Factor" applies a 50% penalty to players already at Top 5 global clubs to ensure the tool focuses on undiscovered talent.

 ## Tech Stack:

- Python

- Pandas, NumPy

- Scikit-learn

- Matplotlib / Seaborn

- Jupyter Notebook

 ## Future Roadmap (Version 2.0)
- Lower League Expansion (Tier 2 Analysis): Expand the scouting engine to high-value developmental leagues like the Dutch Eredivisie, Swedish Allsvenskan, and Portuguese Primeira Liga. These leagues are statistically "physical" and demanding, making them perfect predictors for success in the Top 5 leagues.

- Defensive Disruption Metrics: Integrate tracking data signals like Interception Lanes and Pressure Success Rates to identify undervalued defensive anchors whose contributions don't show up on a standard scoresheet.
