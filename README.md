# 🏏 IPL Analysis Project

An end-to-end Exploratory Data Analysis (EDA) project analyzing historical IPL match data to extract strategic insights regarding team performance, toss dynamics, match-winning trends, and key venue statistics using Python and Pandas.

## Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Research Questions & Key Findings](#research-questions--key-findings)
- [How to Run This Project](#how-to-run-this-project)
- [Final Recommendations](#final-recommendations)
- [Author & Contact](#author--contact)

## Overview
This project evaluates comprehensive IPL tournament history data to derive strategic insights for teams and coaches. A complete analytics pipeline was built using Python and Pandas for data manipulation, handling inconsistencies, cleaning duplicates, and evaluating performance trends across seasons.

## Business Problem
Understanding factors that drive a match win is critical for team optimization, player auctions, and strategic match setups. This analysis aims to solve the following business objectives:
- Identify team performance trends across different seasons.
- Quantify the actual mathematical impact of winning a toss on the final match result.
- Evaluate winning strategies based on match configurations (Batting first vs. Fielding first).
- Investigate ground-specific venue behaviors to help teams select optimal playing squads.

## Dataset
The dataset utilized for this project contains multiple parameters mapping historical match data:
- **File:** `ipl.csv` (Located in the root project folder)
- **Features Included:** `team1`, `team2`, `match_date`, `toss_winner`, `toss_decision`, `winner`, `player_of_match`, `venue`, `city`, `season`, `match_type`, `result`, `result_margin`, `target_runs`, and `target_overs`.

## Tools & Technologies
- **Programming Language:** Python
- **Data Manipulation Libraries:** Pandas, NumPy
- **Version Control & Repository Management:** Git, GitHub

## Project Structure
```directory
EDA-IPL_analysis-py-test/
│
├── README.md                 # Project documentation and summary
├── .gitignore                # Tells Git which files/checkpoints to ignore
├── ipl.csv                   # Raw IPL match records dataset (500+ KB)
└── ipl_analysis.ipynb        # Core Jupyter Notebook executing EDA and cleaning