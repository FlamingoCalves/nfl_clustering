# NFL Team Analysis

![NFL](https://img.shields.io/badge/NFL-Data%20Analysis-brightgreen)

## Overview
This repository contains the code and analysis for clustering NFL teams based on their performance characteristics from the years 2003 to 2019. The analysis provides insights into different team playstyles and success levels, shedding light on the diverse performance profiles of NFL teams over the years.

## Table of Contents
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Findings](#findings)

## Dataset
The dataset used in this analysis includes various statistics for each NFL team, such as wins, losses, offensive plays, turnovers, and more, spanning from 2003 to 2019. The dataset is available as [team_stats_2003_2019.csv](data/team_stats_2003_2019.csv).

## Installation
To run the code and analysis locally, you can follow these steps:
1. Clone this repository to your local machine using `git clone`.
2. Install the required Python libraries listed in `requirements.txt` using `pip install -r requirements.txt`.

## Usage
- [Notebook](nfl_team_analysis.ipynb): The Jupyter Notebook contains the entire data analysis process, from data preprocessing to clustering and visualization.
- [Data](team_stats_2003_2023.csv): The dataset used for the analysis.

## Methodology
1. Data Preprocessing: The dataset was cleaned, and missing values were handled.
2. Feature Selection: Relevant features, including offensive and defensive statistics, penalties, turnovers, and win-loss percentage, were chosen for clustering.
3. K-Means Clustering: K-Means clustering was applied to group NFL teams into distinct clusters. The optimal number of clusters was determined using the elbow method and silhouette analysis.
4. Cluster Analysis & Visualization: Various visualizations, including bar plots and cluster comparisons, were created to understand the clusters.

## Findings
Based on the K-Means clustering analysis, four distinct clusters of NFL teams were identified:
- Cluster 0: Bums - Consistently underperforming teams.
- Cluster 1: Average Teams - Middle-of-the-road NFL teams.
- Cluster 2: Successful Teams - Teams with high Super Bowl victories.
- Cluster 3: Playoff-Caliber Teams - Successful teams with a focus on rushing gameplay.
