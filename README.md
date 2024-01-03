# Collaborative Filtering Recommendation System on CCLE Drug Sensitivity Data

This project implements a Collaborative Filtering Recommendation System using the Cancer Cell Line Encyclopedia (CCLE) dataset. The system aims to predict the sensitivity of cancer cell lines to specific drugs using collaborative filtering techniques.

## Project Overview

- **Objective**: Predicting the sensitivity (rating) of cancer cell lines to anticancer drugs using collaborative filtering.
- **Data Source**: 
  - Barretina,J. et al. (2012) [The Cancer Cell Line Encyclopedia enables predictive modeling of anticancer drug sensitivity. Nature, 483, 603-607](https://www.nature.com/articles/nature11003).
- **Dataset Preprocessing**:
  - The dataset has been preprocessed into IC50 values using the Bayesian sigmoid method.
  - Acknowledgment to C. Suphavilai, D. Bertrand, and N. Nagarajan for their dataset preprocessing work ([Predicting Cancer Drug Response using a Recommender System](https://doi.org/10.1093/bioinformatics/bty452)).

## Project Structure

- `recommendation_system.py`: Python code implementing the collaborative filtering recommendation system.
- `data/`: Contains the preprocessed dataset used for this project.
- `notebooks/`: Jupyter Notebooks used for data exploration and model evaluation.
