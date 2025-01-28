# Football Match Prediction Using Machine Learning and Statistical Techniques with a Focus on Formations

## Overview

This repository contains the research work for the dissertation **"Football Match Prediction Using Machine Learning and Statistical Techniques with a Focus on Formations"**, authored by **Varun Singh** as part of the MSc Big Data Science program.

The study explores the impact of football formations on match outcomes using descriptive statistical analysis and machine learning models. With a focus on formations and team dynamics, the research aims to provide valuable insights for coaches, analysts, and football enthusiasts.

---

## Key Features

- **Formations Analysis**: Statistical insights into how formations influence match results.
- **Machine Learning Models**: Includes models such as Logistic Regression, Random Forest Classifier, SVC, and Gradient Boosting Classifier, achieving a maximum accuracy of 81%.
- **Formation Metrics**: Introduction of formation scores to quantify a team's offensive or defensive style.
- **Dynamic Features**: Predictive features including past match form and formation scores, with weighted calculations for recent matches.

---

## Repository Contents

- **`paper:`**: VarunSingh220054867_MSC_Final
- **`data:`**: PremierLeague_data.xslx
- **`scripts:`**: scrape.ipynb to build the formation database. MSc_final for the modelling
- **`README.md`**: This file.

---

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `beautifulsoup4`


## Results
-The Gradient Boosting Classifier performed best, achieving 81% accuracy.
-Analysis reveals that formations like 3-3-3-1 have higher win percentages compared to others.

-The heatmap included in the results highlights how specific formations perform against one another.

## Applications
**`Coaching & Tactics`**: Provides insights into formation dynamics to aid in pre-match strategies.

**`Analytics`**: Enhances understanding of the relationship between formations and match outcomes.

**`Betting & Predictions`**: Improves predictive accuracy for stakeholders in sports analytics.

## Future Work
The study lays the groundwork for:

-Incorporating dynamic datasets such as video and GPS data.
-Testing models on other leagues like Bundesliga and La Liga.
-Building a recommendation system for player-to-formation fitment.

## Citation
If you use this work, please cite:

@thesis{Singh2025,
  author    = {Varun Singh},
  title     = {Football Match Prediction Using Machine Learning and Statistical Techniques with a Focus on Formations},
  school    = {MSc Big Data Science Program},
  year      = {2025},
}


