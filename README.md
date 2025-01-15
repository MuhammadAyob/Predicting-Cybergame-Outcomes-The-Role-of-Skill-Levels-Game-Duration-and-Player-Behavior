# Predicting Cybergame Outcomes: Skill Levels, Game Duration, and Player Behavior

This project explores the application of machine learning and statistical analysis to predict cybergame outcomes and analyze player performance. By examining 1,119 game records, we provide insights into how skill levels, game duration, and player behavior influence game results, with practical implications for game design and player engagement.

## Overview

### Objectives:
1. **Game Outcome Prediction:** Develop machine learning models to predict whether attackers or defenders will win.
2. **Player Performance Analysis:** Investigate how player skill levels affect offensive and defensive roles.
3. **Impact of Game Duration:** Explore the relationship between game length and outcomes.

### Dataset:
- **Game Records:** 1,119 instances
- **Features:** Player scores, skill levels, game duration, game outcomes (attacker/defender wins)

## Key Features

1. **Machine Learning Models:**
   - **Random Forest**: Achieved perfect classification accuracy.
   - **Stacking Ensemble**: Matched Random Forest in performance.
   - **Naive Bayes**: Strong results but struggled with feature independence assumptions.
   - **Support Vector Machine (SVM)**: Limited performance due to non-linear data.

2. **Statistical Analysis:**
   - **ANOVA Testing:** Significant differences in scores and performance across skill levels.
   - **Correlation Analysis:** Explored relationships between skill levels, scores, and game duration.

3. **Insights:**
   - Higher skill levels correlate with better performance.
   - Defenders excel in longer games, while shorter games favor attackers.

## Methodology

1. **Data Preprocessing:**
   - Encoded categorical variables (e.g., skill levels, game outcomes).
   - Removed outliers using Z-scores.
   - Normalized numeric variables (e.g., scores, game duration).

2. **Exploratory Data Analysis (EDA):**
   - Visualized score distributions and game duration trends.
   - Analyzed skill-level-specific performance patterns.

3. **Model Training and Evaluation:**
   - **Metrics Used:** Accuracy, precision, recall, F1-score.
   - **Train-Test Split:** 80% training, 20% testing.
   - **Cross-Validation:** 5-fold cross-validation for robust performance evaluation.

## Results

1. **Model Performance:**
   - **Random Forest and Stacking Ensemble:** 100% accuracy across all metrics.
   - **Naive Bayes:** 94.1% accuracy with some misclassifications.
   - **SVM:** 64.1% accuracy, struggled with non-linear data.

2. **Skill Level Analysis:**
   - Experts outperformed Beginners and Intermediates in both roles.
   - ANOVA confirmed significant performance differences based on skill levels.

3. **Game Duration:**
   - Longer games favored defenders due to more time for strategic execution.
   - Shorter games benefited attackers with aggressive strategies.

## Practical Implications

1. **Game Design:**
   - Introduce mechanics that reward attackers in longer games to balance gameplay.
   - Adjust difficulty to ensure fair competition across skill levels.

2. **Player Engagement:**
   - Implement matchmaking systems to balance skill levels and enhance player experience.

## Future Directions

1. **Dataset Expansion:**
   - Include more diverse game scenarios and player behaviors.
   - Incorporate granular features like movement patterns and decision points.

2. **Advanced Models:**
   - Explore deep learning or reinforcement learning for enhanced predictions.

3. **Real-Time Systems:**
   - Develop predictive systems for adaptive gameplay and AI-driven assistance.

## Getting Started

### Requirements
- **Languages and Tools:** Python 3.x, Scikit-learn, Pandas, Matplotlib, Seaborn.
- **Dataset:** Provided in `data/` directory.


