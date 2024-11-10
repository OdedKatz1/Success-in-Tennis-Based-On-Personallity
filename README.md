# Success in Tennis Based On Personallity
## Project Overview
This project explores the potential to predict the success of tennis players based on their personality traits, as inferred from interview responses. By analyzing linguistic features in players' interviews, we aim to identify psychological indicators that correlate with athletic success, specifically focusing on achieving a top-tier global ranking.
## Data Collection
- **Source:** Interviews were collected from the ASAP Sports website, with a focus on players who have been ranked globally.
- **Scope:** Interviews were taken after both wins and losses, focusing on early-career games
- **Sample:** 417 players, with four interviews per player, ensuring a equal number of wins and loses to ensure a balance between positive and negative emotional content.
## Features
### Personality Traits
Using advanced language models (LLMs), we extracted key personality traits aligned with the Big Five model and additional traits identified in sports psychology literature, such as self-confidence, persistence, and competitiveness.
### Textual and Demographic Features
- **Linguistic Inquiry and Word Count (LIWC)** was used to quantify word categories related to psychological attributes (e.g., positive/negative emotion, power, affiliation).
- **Demographics:** Year of birth, dominant hand, and height and more.
- **Additional Textual Features:** Metrics such as the ratio of player responses relative to interview length were included to gauge expressiveness.
## Model Training
Three machine learning models were evaluated:
1.	**Support Vector Machine (SVM)**
2.	**Logistic Regression** (final model chosen based on best F1-score)
3.	**K-Nearest Neighbors (KNN)**
## Model Performance
Using 10-fold cross-validation and F1 as the primary performance metric, logistic regression demonstrated the most stable results across all folds.
## Results
Key predictive features included:
- LIWC-derived categories (e.g., power, analytic thinking, mental focus).
- Big Five trait scores, specifically lower neuroticism.
- Demographic features, with an interesting correlation between older birth years and elite ranking likelihood.
## Conclusion
Our findings indicate a meaningful relationship between psychological traits and tennis success, aligning with previous research that suggests lower neuroticism and higher self-confidence are common in elite athletes.
## Future Work
Further analysis with expanded datasets and refined feature engineering could provide more robust predictions and deeper insights into personality's role in athletic achievement.
## Acknowledgments
- **Special thanks** to my lecturers, Mattan Ben-Shachar and Michael Gilead, for their guidance and support throughout this course, which was fundamental in shaping and completing this project.
- **Datasets:** Tennis player data provided by Jeff Sackmann on GitHub (ATP, WTA)
- **References:** Research articles and psychological frameworks cited throughout the study.

For a more detailed overview please check the final paper under the "Predicting" folder (written in Hebrew).