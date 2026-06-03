# IPL Exploratory Data Analysis (EDA)

Welcome to the IPL Exploratory Data Analysis repository. This project dives into ball-by-ball data from the Indian Premier League (IPL) to uncover trends, team performances, and strategic insights[cite: 1].

## Dataset Overview

The analysis is built on a comprehensive dataset encompassing 1,218 matches and 289,673 individual deliveries, resulting in over 8.4 million data points[cite: 1].

### Data Preprocessing

To ensure accuracy in the visualizations and aggregations, extensive data cleaning was performed[cite: 1]:

- **Team Name Standardization**: Historical and inconsistent team names were updated to their current iterations (e.g., 'Delhi Daredevils' to 'Delhi Capitals', 'Kings XI Punjab' to 'Punjab Kings')[cite: 1].
- **Venue Consolidation**: Inconsistent stadium names and cities were unified (e.g., merging various names for the M Chinnaswamy Stadium, Eden Gardens, and Rajiv Gandhi International Stadium)[cite: 1].
- **Season Normalization**: Cross-year season formats like '2007/08' and '2020/21' were standardized to single years for cleaner time-series grouping[cite: 1].
- **Missing Values**: Addressed null values in categories such as city, player of the match, and wicket details[cite: 1].

---

## Visualizations & Key Insights

### 1. The Impact of the Toss

Does winning the toss actually win you the match? We analyzed the toss win rates and subsequent match outcomes across all franchises[cite: 1].

- The data suggests that winning the toss barely matters on its own, but the decision made afterward is critical[cite: 1].
- Historically, teams that choose to field after winning the toss experience a notably higher match win rate compared to those who choose to bat[cite: 1].

![Toss Analysis](toss.png)

### 2. Match Phase Analysis

Breaking down the game into distinct phases (such as the Powerplay, Middle Overs, and Death Overs) reveals how different teams approach pacing, run-accumulation, and wicket preservation.

![Match Phase Analysis](phase_analysis.png)

Further deep-dives into phase-specific metrics highlight the contrast in batting aggression and bowling economy as the innings progresses.

![Match Phase Analysis 2](phase_analysis_2.png)

---

## Tech Stack

- **Language**: Python[cite: 1]
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn[cite: 1]

## Getting Started

1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed:

```bash
   pip install pandas numpy matplotlib seaborn
```
