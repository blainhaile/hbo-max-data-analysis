# HBO Max Data Analysis Project

This repository contains an analysis of the HBO dataset, exploring trends, ratings, and other insights.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Overview](#data-overview)
3. [Analysis Steps](#analysis-steps)
4. [Key Findings](#key-findings)
5. [How to Reproduce](#how-to-reproduce)
6. [Visualizations](#visualizations)

---

## Project Overview

This project analyzes an HBO dataset with titles, ratings, genres, votes, and other features to derive meaningful insights. The analysis includes:
- Descriptive analysis of titles by type and genre.
- Trends in ratings and votes over time.
- Correlation between votes and ratings.
- Genre-specific insights.

---

## Data Overview

The dataset includes:
- **5416 unique titles** (1746 TV shows, 3670 movies).
- Information on genres, release year, average ratings, and votes.

### Sample Data

| Title                 | Type  | Genres                  | Release Year | Average Rating | Votes   |
|-----------------------|-------|-------------------------|--------------|----------------|---------|
| The Shawshank Redemption | Movie | {Drama, Crime}        | 1994         | 9.3            | 2961822 |

---

## Analysis Steps

1. **Descriptive Analysis**:
   - Count of titles by type and genre.
   - Identification of top and bottom-rated titles.

2. **Rating Analysis**:
   - Average ratings by type and genre.
   - High-rated vs. low-rated titles.

3. **Engagement Analysis**:
   - Most voted titles.
   - Correlation between votes and ratings.

4. **Trends Over Time**:
   - Titles and ratings by release year.

5. **Genre-Based Insights**:
   - Popular genres over time.
   - Multi-genre title trends.

---

## Key Findings

- **Top Rated Title**: _Treme_ (9.4 average rating).
- **Most Voted Title**: _The Shawshank Redemption_ (2,961,822 votes).
- **Highest Average Rating Year**: 1942 (8.5 average).
- **Most Common Genre Combination**: _Documentary_ (425 titles).

### Visualizations

Check out the Tableau dashboard [here](https://public.tableau.com/views/HBOMaxDashboard_v2024_2/HBODashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

---

## How to Reproduce

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hbo-data-analysis.git
