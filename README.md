# Success in Tennis Based On Personallity
The following project tries to predict if a tennis players will reach top-level (= will have a top rating of at least 8) based on their media interviews and demographic characteristics using ML algorithms, psychological dictionaries and LLMs, written in Python and R.
## Project overview & workflow:
- "Interviews": Scraping and processing tennis players interviews using BeautifulSoup.
- "Players Data Frame": Extracting personality and demogrphic traits for each player based on the interviews using Google's Gemini, LIWC dictionary and Panads.
- "Predicting": Training serval models to predict tennis players success. KNN, Logistic Regression and SVM using caret, rsample, tidyverse etc..

For a more detailed overview please check the final paper under the "Predicting" folder (written in Hebrew).

