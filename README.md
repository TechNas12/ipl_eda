
# IPL Exploratory Data Analysis

## Overview
This repository contains an in-depth Exploratory Data Analysis (EDA) of the Indian Premier League (IPL)[cite: 1]. Using ball-by-ball data, this project goes beyond traditional statistics to analyze the true impact of the toss and the critical phases of an IPL match. The analysis spans across 1,218 matches[cite: 1], providing a comprehensive look at what actually drives winning outcomes in T20 cricket.

## Dataset
* **Source:** Cricsheet IPL ball-by-ball dataset[cite: 1]
* **Scope:** 1,218 IPL matches[cite: 1]

## Key Insights & Visualizations

### 1. The Toss Illusion: Does Winning the Toss Matter?
A common narrative in T20 cricket is that winning the toss provides a massive advantage. The data tells a different story.

![Toss Analysis](toss.png)

* **Overall Impact:** Across 1218 matches, the team winning the toss wins the match only **50.5%** of the time[cite: 1]—essentially a coin flip.
* **The Decision:** What you do after winning the toss matters more[cite: 1]. Teams choosing to field win at a higher rate (53.7%) compared to those choosing to bat (44.3%)[cite: 1].
* **Team Efficiency:** Chennai Super Kings (CSK) capitalizes on winning the toss better than any other team, with a 60.0% win rate when the coin falls in their favor[cite: 1].

---

### 2. The Three-Act Breakdown: Which Phase Wins Matches?
T20 innings can be broken down into three acts: Powerplay (Overs 0-5), Middle Overs (Overs 6-15), and Death Overs (Overs 16-19)[cite: 1].

![Phase Analysis](phase_analysis.png)

* **The Middle Over Dominance:** Dominating the middle overs yields the highest win probability (**54.8%**)[cite: 1]. It is also the phase most responsible for flipping the momentum if a team loses the powerplay, causing 55.9% of powerplay flips[cite: 1].
* **The Collapse Effect:** Losing 3 or more wickets in *any* phase drastically kills your win probability, with a massive -24.2% drop in win chance if the collapse happens during the powerplay[cite: 1].

---

### 3. Building the Platform: The Anatomy of a Winning Innings
While the death overs are where matches are finished, the platform must be built effectively. 

![Phase Analysis 2](phase_analysis_2.png)

* **Run Separation:** The middle overs are where winners separate themselves from losers the most in terms of average runs scored[cite: 1].
* **Wicket Preservation:** Winning teams consistently protect their wickets better in the powerplay and middle overs (averaging only 1.1 and 2.2 wickets lost, respectively)[cite: 1]. 
* **Death Over Acceleration:** Because winners protect their wickets early, they are able to accelerate much harder in the death overs, achieving an average run rate of **11.0** compared to the losers' 8.9[cite: 1].

## Getting Started

### Prerequisites
To run the analysis notebooks, you will need the following libraries:
* Python 3.8+
* Pandas[cite: 1]
* Matplotlib[cite: 1]
* Seaborn[cite: 1]
* NumPy[cite: 1]

### Installation
1. Clone the repository:
```bash
   git clone [https://github.com/TechNas12/ipl_eda.git](https://github.com/TechNas12/ipl_eda.git)

```

2. Navigate to the project directory:

```bash
   cd ipl_eda

```

3. Install the required dependencies:

```bash
   pip install -r requirements.txt

```

*(Note: Ensure the Cricsheet dataset is downloaded and placed in the appropriate `data/` folder before running the notebooks.)*

```

```
