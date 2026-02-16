Name: Johana Rivera Joachin

Course Name: CS 4379G Data Analysis and Visualization

Description: This repository contains my first assignment for CS4379G. Demonstrating basic git operations such as 
repository initialization, commits, and pushing to a remote gitHub repository. While also, building a clean analysis
notebook with reproductive steps.

Dataset:
The analysis uses the "Netflix Movies and TV Shows" dataset from Kaggle:
https://www.kaggle.com/datasets/shivamb/netflix-shows

How to Run:
1. Clone this repository.
2. Download `netflix_titles.csv` from the Kaggle link above and place it in `data/netflix/`.
3. Open `notebooks/analysis.ipynb` in Jupyter Notebook 
4. Run all cells 
5. Required libraries: `pandas`, `numpy`, `matplotlib`.

Findings:
- Netflix added an increasing number of titles from 2015 to 2019, with a decline in 2020–2021, likely due to COVID-19
  impacts or incomplete data. Movies consistently outnumber TV Shows in yearly additions.
- The average Netflix movie is around 100 minutes long, while most TV Shows have just 1–2 seasons.
- TV-MA is the most common rating for both Movies and TV Shows. Movies have a broader range of ratings
  (including R and PG-13), while TV Shows are more concentrated in TV-MA and TV-14.
