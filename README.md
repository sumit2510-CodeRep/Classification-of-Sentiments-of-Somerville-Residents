# Classification-of-Sentiments-of-Somerville-Residents
Our goal is to predict the sentiment of the residents of Somerville based on the inputs given by the residents during the survey. We will classify if the residents are happy or unhappy based on 28 inputs out of 54 from the survey.

The data is retrived from real-time survey data from https://data.somervillema.gov/Happiness/Somerville-Happiness-Survey-Responses/bi8e-5vw8
We want to find the most relevant columns with respect to our class attribute so that we can predict the class attribute more efficiently using the reduced dataset which contains only the most important columns. Hence, reducing the runtime of the algorithm.

We are also trying to find the most efficient algorithm (KNN, Decision Tree, Random Forest, Naïve Bayes, Neural Networks) to predict the class attribute for our dataset using cross fold validation and testing various scenarios based on the reduced dataset that we are generating using attribute selection methods (Pearson Correlation, Chi-Squared, Recursive Feature Elimination, L1-based feature selection, Tree-based feature selection).
